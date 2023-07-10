# To-Do Recorder Challenge

Implemented a simple todo app with the possibility to record user actions and play them back to the user. Made for a job interview coding test in March 2020.

## Bundle process

To build both development and production bundles (found in **build/production /development**), run:

### npm run build

## Tests

To run unit tests:

### npm test

## Coding test specifications

- create a ReactJS SPA todo app: CREATE/UPDATE/DELETE actions, basic todo properties
- add recording functionality that records users actions when pressing a record button
- user can play actions back in correct order with 1 second interval between each action as it was recorded
- any recording should be stored - should remain if browser is refreshed

## Requirements for coding test

- app should work exactly as per specs
- app should be responsive
- unit testing with full code coverage
- no scaffold to generate app e.g. no create-react-app, webpack config must be written from scratch
- bundle process: both dev and prod versions created as a result of build process, dev build should allow any developer to debug in a browser, prod build should focus on size and speed of loading in browser
- only CSS, no libraries allowed (e.g. bootstrap)

## Improvements

- **Design** - could be improved by implementing toggles to display only active todos or completed todos etc. Animations could be added to make the played user actions look less static while updating the UI.

- **Functionality** - the recording functionality could be used as a session history to allow the user to undo/redo their actions.
