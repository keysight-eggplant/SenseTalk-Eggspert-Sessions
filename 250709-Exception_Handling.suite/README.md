# Notes

[![](https://img.shields.io/badge/YouTube-13m24s-FF0000?logo=youtube)](https://youtu.be/KhznJRITALg)

Join Eggplant Research and Developer, Doug Simons, to learn more about Eggplant's English-like language **SenseTalk** and its capabilities.

### Topics
- Understanding runtime exceptions and what causes them
- Using `try/catch/end try` to intercept and handle exceptions gracefully
- Using `try` without `catch` to silently suppress errors
- Single-statement form: `try to <command>`
- Catching exceptions into a named variable with `catch exceptionVar`
- Using `the exception` global property to inspect the caught exception
- Examining the exception object's properties: `.name`, `.reason`, `.location`, `.scriptError.line`
- Throwing custom exceptions with `throw` (name and reason)
- Re-throwing a caught exception after modifying it
- Controlling `ThrowExceptionResults` to receive exceptions as return values instead of thrown errors
- Testing `the result` with `is an exception`

### Helpful Links
- [Sensetalk Travel Guide](https://docs.eggplantsoftware.com/studio/stk-sensetalk-travel-guide/)
- [Error Handling in SenseTalk](https://docs.eggplantsoftware.com/studio/stk-error-handling/)
- [Global Properties for Objects, Messages, and Results](https://docs.eggplantsoftware.com/studio/stk-global-properties-object-messages-results/)
