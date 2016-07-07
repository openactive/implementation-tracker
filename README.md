## [Activation Issue Tracker](https://github.com/openactive/activation/issues) for Openactive Implementations

[//]: # (Below the SNIP is included in Openactive.io)
[//]: # (_SNIP_)

We encourage you to make use of the [Activation Issue Tracker](https://github.com/openactive/activation/issues). For new implementations, please post an example JSON response (even if hypothetical, before work has begun) with a link to your test environment if appropriate, with the "example" label, for the community to comment on.

#### Labels to use

- *example*: For new implementations, please post an example JSON response (even if hypothetical, before work has begun) with a link to your test environment if appropriate, with the "example" label, for the community to comment on. We will then create a milestone associated with your implementation and raise any issues against that.
- *question*: For any questions about implementation in general, please raise an issue with a "question" label.
- *bug*: Issues that the community spot with a particular implementation are raised as bugs against the milestone related to that implementation.
- *enhancement*: Requests for additional data from a particular data source are made via "enhancements" against the milestone related to that implementation.
- *help wanted*: For help required from the community, please detail the request.

#### Implementation checklist

Before posting the example implementation, check the following common issues have been included in your thinking:

- Date formats, are you using the ISO 8601?
- Are records deleted from your system marked with a deleted flag and included in the "Deleted" state
- Does your feed include all historical data from the beginning of time and not just data in the future or from today's date
- Have you included as much data as possible
- Does your implementation match your internal state as closely as possible (i.e. you are not generating sessions that don't actually yet exist as records in your system from a recurrance rule, but are instead providing the recurrance rule).
- Does each page contain a licensing key?
- Are Session URLs are included in the data block for each session, so a user can find out details from source?
- Is the Next URL present on the last page?
- Are HTML or Markdown encoded data fields included in plain as well as raw form as separate fields?
