# Service Portal Snippets for VS Code

This extension for Visual Studio Code adds a handy collection of ServiceNow [Service Portal](https://docs.servicenow.com/bundle/london-servicenow-platform/page/build/service-portal/concept/c_ServicePortal.html) snippets. The snippets adhere to best practice by following the [Service Portal: AngularJS Style Guide](https://github.com/platform-experience/serviceportal-best-practice).

See the [CHANGELOG](CHANGELOG.md) for the latest changes

## Usage

To generate a snippet, simply type part of the snippet and press `enter`.

### HTML Snippets

| Snippet                   | Purpose                                    |
| ------------------------- | ------------------------------------------ |
| `sp-embed-widget`         | Embed a widget using `<widget>`            |
| `sp-embed-widget-spUtil`  | Embed a widget using `<sp-widget>`         |
| `sp-ng-class-attribute`   | `ng-class` with attribute                  |
| `sp-ng-class-css`         | `ng-class` with CSS class                  |
| `sp-ng-if`                | `ng-if`                                    |
| `sp-ng-include`           | `ng-include`                               |
| `sp-ng-repeat`            | `ng-repeat`                                |
| `sp-ng-repeat-orderBy`    | `ng-repeat` with orderBy                   |
| `sp-ng-repeat-track-by`   | `ng-repeat` with track by                  |
| `sp-ng-repeat-combo`      | `ng-repeat` with orderBy and track by      |

### CSS Snippets

| Snippet                   | Purpose                                    |
| ------------------------- | ------------------------------------------ |
| ``                        |                                            |

### Client Snippets

| Snippet                   | Purpose                                    |
| ------------------------- | ------------------------------------------ |
| `sp-broadcast-event`      | `$broadcast`                               |
| `sp-controller`           | Creates a client controller                |
| `sp-embed-widget`         | Embed a widget in the client script        |
| `sp-embed-widget-options` | Embed a widget with options                |
| `sp-emit-event`           | `$emit`                                    |
| `sp-on-event`             | `$on`                                      |
| `sp-onInit`               | `$onInit`                                  |
| `sp-record-watcher`       | Tool to capture real-time table updates    |

### Server Snippets

| Snippet                   | Purpose                                    |
| ------------------------- | ------------------------------------------ |
| `sp-getDisplayName`       | Get the current user's display name        |
| `sp-getEmail`             | Get the user's email address               |
| `sp-getFirstName`         | Get the user's first name                  |
| `sp-getID`                | Get the sys_id of the current user         |
| `sp-getLastName`          | Get the user's last name                   |
| `sp-getUserName`          | Get the user's username                    |
| `sp-hasRole`              | Determines if a user has a specified role  |
| `sp-isMemberOf`           | Checks if the user is a member of a group  |

### UI Script Snippets

| Snippet                   | Purpose                                    |
| ------------------------- | ------------------------------------------ |
| `sp-component`            | Creates an AngularJS component             |
| `sp-module`               | Creates an AngularJS module                |
| `sp-service`              | Creates an AngularJS service               |
