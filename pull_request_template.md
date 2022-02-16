## Proposed changes

Describe the big picture of your changes here to communicate to the maintainers why we should accept this pull request. If it fixes a bug or resolves a feature request, be sure to link to that issue. Please ensure the "what" and "why" are explained properly in this description as it will be used as the commit description on squashing your pull request commits. 

### Your checklist for this pull request

_Put an `x` in the boxes that apply. You can also fill these out after creating the PR. If you're unsure about any of them, don't hesitate to ask. We're here to help! This is simply a reminder of what we are going to look for before merging your code._

**Contributor**:
- [ ] PR is well described and the description can be used as a commit message on squash
- [ ] Related issues linked to PR if existing and labels set
- [ ] New code is covered with unit tests
- [ ] New/updated ui components are tested inside the storybook (module ui-components only) 
- [ ] [Changelog entry file](https://github.com/scm-manager/changelog#changelog-entry-files) created in `gradle/changelog`
- [ ] Feature has been tested with different permissions
- [ ] Documentation updated (only necessary for new features or changed behaviour)

**Reviewer**:
- [ ] The clean code principles are respected ([CleanCode](https://clean-code-developer.com/virtues/))
- [ ] All new code/logic is implemented on the right spot / "Should this be done here?"
- [ ] UI changes fits into the layout
- [ ] The UI views / components are responsive (mobile views)
- [ ] Correct translations are available

### Checklist for branch merge request (not required for forks)

- [ ] Branch is green/blue on [Jenkins](https://oss.cloudogu.com/jenkins/)
- [ ] Quality Gate passed on [SonarQube](https://sonarcloud.io/organizations/scm-manager/projects)
