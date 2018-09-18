# Service Portal Snippets for VS Code

This extension for Visual Studio Code adds a handy collection of ServiceNow [Service Portal](https://docs.servicenow.com/bundle/london-servicenow-platform/page/build/service-portal/concept/c_ServicePortal.html) snippets. The snippets adhere to best practice by following the [Service Portal: AngularJS Style Guide](https://github.com/platform-experience/serviceportal-best-practice).

See the [CHANGELOG](CHANGELOG.md) for the latest changes

## Usage

To generate a snippet, simply type part of the snippet and press `enter`.

### HTML Snippets

| Snippet                          | Purpose                                    |
| -------------------------------- | ------------------------------------------ |
| `sp-ng-class-attribute`          | `ng-class` with attribute                  |
| `sp-ng-class-css`                | `ng-class` with CSS class                  |
| `sp-ng-if`                       | `ng-if`                                    |
| `sp-ng-include`                  | `ng-include`                               |
| `sp-ng-repeat`                   | `ng-repeat`                                |
| `sp-ng-repeat-combo`             | `ng-repeat` with orderBy and track by      |
| `sp-ng-repeat-orderBy`           | `ng-repeat` with orderBy                   |
| `sp-ng-repeat-track-by`          | `ng-repeat` with track by                  |
| `sp-modal-alert`                 | Displays an alert                          |
| `sp-modal-confirm`               | Displays a confirmation message            |
| `sp-modal-open`                  | Opens a modal window using options         |
| `sp-modal-prompt`                | Displays a prompt for user input           |
| `sp-tag-embed-widget`            | Embed a widget using `<widget>`            |
| `sp-util-embed-widget`           | Embed a widget using `<sp-widget>`         |

### CSS Snippets

| Snippet                          | Purpose                                    |
| -------------------------------- | ------------------------------------------ |
| ``                               |                                            |

### Client Snippets

| Snippet                          | Purpose                                    |
| -------------------------------- | ------------------------------------------ |
| `sp-ng-broadcast`                | `$broadcast`                               |
| `sp-ng-controller`               | Creates a client controller                |
| `sp-ng-emit`                     | `$emit`                                    |
| `sp-ng-http`                     | `$http`                                    |
| `sp-ng-on`                       | `$on`                                      |
| `sp-ng-onInit`                   | `$onInit`                                  |
| `sp-modal-alert`                 | Displays an alert                          |
| `sp-modal-confirm`               | Displays a confirmation message            |
| `sp-modal-open`                  | Opens a modal window with embedded widget  |
| `sp-modal-prompt`                | Displays a prompt for user input           |
| `sp-util-addErrorMessage`        | Displays a notification error message      |
| `sp-util-addInfoMessage`         | Displays a notification info message       |
| `sp-util-addTrivialMessage`      | Displays a trivial notification message    |
| `sp-util-get`                    | Embed a widget in the client script        |
| `sp-util-get-options`            | Embed a widget with options                |
| `sp-util-record-watch`           | Tool to capture real-time table updates    |

### Server Snippets

| Snippet                          | Purpose                                    |
| -------------------------------- | ------------------------------------------ |
| `sp-record-addActiveQuery`       | Adds a filter to return active records     |
| `sp-record-addEncodedQuery`      | Adds an encoded query to other queries     |
| `sp-record-create`               | Creates a GlideRecord class for a table    |
| `sp-record-deleteMultiple`       | Deletes multiple records                   |
| `sp-record-deleteRecord`         | Deletes the current record                 |
| `sp-record-get`                  | A method used to query for single record   |
| `sp-record-getRowCount`          | Get the number of rows for a query result  |
| `sp-record-insert`               | Inserts a new record                       |
| `sp-record-setLimit`             | The maximum number of records to fetch     |
| `sp-record-update`               | Updates the current record                 |
| `sp-record-updateMultiple`       | Updates multiple records                   |
| `sp-user-getDisplayName`         | Get the current user's display name        |
| `sp-user-getEmail`               | Get the user's email address               |
| `sp-user-getFirstName`           | Get the user's first name                  |
| `sp-user-getID`                  | Get the sys_id of the current user         |
| `sp-user-getLastName`            | Get the user's last name                   |
| `sp-user-getUserName`            | Get the user's username                    |
| `sp-user-hasRole`                | Determines if a user has a specified role  |
| `sp-user-isMemberOf`             | Checks if the user is a member of a group  |

### UI Script Snippets

| Snippet                          | Purpose                                    |
| -------------------------------- | ------------------------------------------ |
| `sp-ng-component`                | Creates an AngularJS component             |
| `sp-ng-module`                   | Creates an AngularJS module                |
| `sp-ng-service`                  | Creates an AngularJS service               |

## Installation

```
Mac:      Select ⌘+P and then type: ext install service-portal-snippets
Windows:  Select Ctrl+P and then type: ext install service-portal-snippets
```

Alternatively, simply bring up the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of VS Code; then browse for Service Portal Snippets and hit the install button.

## Pro Tip

Simply type the snippet without dashes to activate intellisense.

## License

[MIT License](LICENSE)