# What are the differences between profile and session ID:

- **Session IDs**:
  - Generated on the client side when a user opens a browser or app.
  - Used to track a user's visit or session.
  - Stored in a cookie in the user's browser.
  - Erased when the browser or app is closed.
  - New session ID generated on each new visit.
  - Controlled by client-side scripts.

- **Profile IDs**:
  - Generated by Tracardi when a user interacts with the website or app.
  - Used to create a user profile and store user data.
  - Stored in the local storage of the browser.
  - Remains constant across multiple visits and devices.
  - Bound to the browser but can be merged into a single profile.
  - Managed by Tracardi and used for identity resolution.
