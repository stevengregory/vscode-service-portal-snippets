# Service Portal Snippets for VS Code

This extension for Visual Studio Code adds a handy collection of ServiceNow [Service Portal](https://docs.servicenow.com/bundle/london-servicenow-platform/page/build/service-portal/concept/c_ServicePortal.html) snippets. The snippets adhere to best practice by following the [Service Portal: AngularJS Style Guide](https://github.com/platform-experience/serviceportal-best-practice).

See the [CHANGELOG](CHANGELOG.md) for the latest changes

## Usage

To generate a snippet, simply type part of the snippet and press `enter`.

### HTML Snippets

| Snippet                          | Purpose                                    |
| -------------------------------- | ------------------------------------------ |
| `sp-element-embed-widget`        | Embed a widget using `<widget>`            |
| `sp-spUtil-embed-widget`         | Embed a widget using `<sp-widget>`         |
| `sp-ng-class-attribute`          | `ng-class` with attribute                  |
| `sp-ng-class-css`                | `ng-class` with CSS class                  |
| `sp-ng-if`                       | `ng-if`                                    |
| `sp-ng-include`                  | `ng-include`                               |
| `sp-ng-repeat`                   | `ng-repeat`                                |
| `sp-ng-repeat-combo`             | `ng-repeat` with orderBy and track by      |
| `sp-ng-repeat-orderBy`           | `ng-repeat` with orderBy                   |
| `sp-ng-repeat-track-by`          | `ng-repeat` with track by                  |

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
| `sp-ng-on`                       | `$on`                                      |
| `sp-ng-onInit`                   | `$onInit`                                  |
| `sp-spUtil-addErrorMessage`      | Displays a notification error message      |
| `sp-spUtil-addInfoMessage`       | Displays a notification info message       |
| `sp-spUtil-addTrivialMessage`    | Displays a trivial notification message    |
| `sp-spUtil-get`                  | Embed a widget in the client script        |
| `sp-spUtil-get-options`          | Embed a widget with options                |
| `sp-spUtil-record-watch`         | Tool to capture real-time table updates    |

### Server Snippets

| Snippet                          | Purpose                                    |
| -------------------------------- | ------------------------------------------ |
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
