## [0.9.0] - 2017-10-09

- API: move actions from client into report (@esjee)

This is a breaking change, but this is still not a 1.0 and shouldn't be considered stable.

## [0.8.0] - 2017-09-05

- Feature: add ability to suggest and award swag, cash, and bonuses (@esjee)

## [0.7.0] - 2017-08-28

- Feature: retrieve common responses (@esjee)

## [0.6.0] - 2017-07-24

- Feature: comments (internal or not) can be added to reports

## [0.5.2] - 2017-07-19

- Bugfix: structured scopes were not being populated correctly resulting in nil results for all attributes

## [0.5.1] - 2017-06-26

- [Structure scope](https://api.hackerone.com/docs/v1#structured-scope) data added to report object

## [0.5.0] - 2017-06-23

- `report.assign_to_user` and `report.assign_to_group` (@esjee)

## [0.4.0] - 2017-04-21

- `client.reporters` to return all reporters for a given project (@esjee)
- `HackerOne::Client::Program.find(program_name)` to return information about a given program (@esjee)
