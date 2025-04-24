Please see the [contributing guidelines](CONTRIBUTING.md) for how to create and submit a high-quality PR for this repo.
How to name my PR?

Avoid specifying implementation details in the PR title. The PR title should reflect behavior changes.

- Fixed bug: "Fixed bug where &lt;what happens&gt; &lt;can rarely (if applicable)&gt; when &lt;when it happens&gt;". For example: "Fixed bug where sniffer would not stop gracefully upon context cancellation"
- New feature: "Added support for &lt;new scenario that works, worded from the user's perspective&gt;", "Support for &lt;new feature&gt;". For example: "Support for GCP IAM eBPF visibility", "Support new API version for ClientIntents: v2beta1"
- Improvement to existing feature: "Improve &lt;what&gt; by &lt;doing what&gt;". For example: "Improve CPU consumption by skipping populateReferencedKubernetesServices logic when egress enforcement is disabled" 

### Description

Describe the purpose of this PR along with any background information and the impacts of the proposed change. For the benefit of the community, please do not assume prior context.

Provide details that support your chosen implementation, including: breaking changes, alternatives considered, changes to the API, etc.


### References

Include any links supporting this change such as a:

- GitHub Issue/PR number addressed or fixed
- StackOverflow post
- Related pull requests/issues from other repos

If there are no references, simply delete this section.

### Testing

Describe how this can be tested by reviewers. Be specific about anything not tested and reasons why. If this library has unit and/or integration testing, tests should be added for new functionality and existing tests should complete without errors.

Please include any manual steps for testing end-to-end or functionality not covered by unit/integration tests.

Also include details of the environment this PR was developed in (language/platform/browser version).

- [ ] This change adds test coverage for new/changed/fixed functionality

### Checklist

- [ ] I have added documentation for new/changed functionality in this PR and in github.com/otterize/docs
