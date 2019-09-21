# Email Recipient List Task:
This project is done as a squeleton for a frontend angular exibition.
### User Story:
As a User I want to be able to select recipients and get a list of companies I can still add. It
should also be possible to add email recipients as long as the given email is valid.
Acceptance Criteria:
- I can enter the name of a company inside the autocomplete and select suggestions
which are then added on the right side.
- I can enter any email address in the autocomplete. The autocomplete will allow me to
add the email address to the list once it is valid (Definition of valid: min 1. character
before @ sign and valid domain including at least a 2 character tld after @ sign)
- Selected options are not displayed anymore in the autocomplete
- Selected recipients are grouped in company and email recipients
- When multiple email recipients share the same domain, they are grouped under a
single domain group which only shows the domain
- Domain groups are expandable and retractable and show the contained recipients
- I can remove selected recipients by pressing the X icon. A click on a single email of a
domain group only removes that email address from the group.
- A total count of all selected recipients is displayed next to the selected recipients
header.
- (Optional) Available recipient lists are displayed
- (Optional) When I select a recipient list, all company and email recipients contained
in it are added

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
