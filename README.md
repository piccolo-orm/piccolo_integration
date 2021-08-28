# Piccolo Integration

The aim of this repo is to setup a GitHub action which will do the following:

 * Install Piccolo, Piccolo API, and Piccolo Admin, from their GitHub master branches.
 * Make sure the Piccolo CLI runs correctly.
 * Run the Cypress integration tests from Piccolo Admin.

This would provide a great deal of confidence that the entire stack works as expected.

It could be triggered manually before releasing any of the Piccolo libraries. It seems like GitHub Actions [supports manual triggers](https://docs.github.com/en/actions/reference/events-that-trigger-workflows#manual-events).

The project is still in the research phase, and input is welcome from anyone with knowledge of GitHub Actions and / or Cypress.
