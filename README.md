# Roadmap
## Process and Tools
The Notary V2 team uses the [Roadmap GitHub Project Board](https://github.com/iamsamirzon/roadmap/projects/1) to track short term (1-3 months) and medium term (3-6 months) efforts and long term (6-12 months). Once a broad objective (from the "Future/Backlog" column) is further scoped into a GitHub issue that has a clear objective, background and motive, it is moved into the "To do" column. From there, the team plans releases via [GitHub Milestones](https://github.com/iamsamirzon/roadmap/milestones).

## Current and Future Objectives
At this time, the Notary community is working on NotaryV2 specification  and two separate sub projects, TUF and Notation. This roadmap is focused  on the NotaryV2 specification  and Notation

### Current (Short term) Focus
- Putting Alpha Release(s) out of Notation for early feedback and testing. Multiple "alpha" milestones are tracking to it and each milestone will be accompanied by one release
- Iterate on the Notary V2 specification and be done with the alpha releases. 
- Collaborate with other open source projects for co-related/dependent features needed for end to end use case of OCI artifacts signing

### Future (Mid to Long term) Focus
- Release the first [GA version of the Notary V2 specification and Notation](https://github.com/iamsamirzon/ForTestPurpose/projects/1). This milestone is marked as "RC-1"
- Iterate on supporting additional signature formats in the specification
- Support Revocation in the Notation Client

### Leading up to the first official release
*At present four milestones are planned leading up to the first release. During each milestones, backwards compatabilty is not guranteed. CLI clients and SDK will be iterated. Test cases will be added along the way.*
- alpha-1 : Goal - Get feedback on the notation CLI client and notation implementation at the earliest
- alpha-2 : Goal - Merge open PR on the NotaryV2 standard, CLI and Notation specfications; 
- alpha-3 : Goal - Finalize the Signature Format (including Payload and Manifest), revocation, and scoped signature verification policy; Finalize local storage for CLI client
- RC-1    : Goal - This is the first release, also referred it as the GA release. Will use the finalized signature format; Notation integration with remote key stores and signing services



## Getting Involved

Please file [GitHub issues](https://github.com/notaryproject/notaryproject/issues) to propose features and identify bugs. See more information about how to get involved with the community [here](https://github.com/notaryproject).