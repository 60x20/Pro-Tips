# JS

## Events

- Methods like click(), focus(), blur() trigger events. Though focus-related methods won't trigger events if executed from dev-tools, until the window gets the focus. [Related](https://github.com/testing-library/user-event/issues/553).
- Changing the "value" property of an input does not trigger events. (inputElement.value = "value").
