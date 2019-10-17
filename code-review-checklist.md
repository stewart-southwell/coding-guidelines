# Code Review Checklist
### Naming convention
- &#9745; Use self-explanatory names for everything (interfaces, classes, methods, variables etc.).
- &#9745; Use Pascal casing for all public member, type, and namespace names consisting of multiple words. Use Camel casing for parameter names.
- &#9745; Name classes and structs with nouns or noun phrases. Name methods with verbs or verb phrases.
- &#9745; Prefix interface names with the letter I, to indicate that the type is an interface.
- &#9745; Suffix asynchronous method name by "Async".

### Coding best practices
- &#9745; Write methods which do one and only one job.
- &#9745; Public methods must validate their input arguments.
- &#9745; Report execution failures by throwing exceptions.
- &#9745; Write comments which describe what the code does and/or whyit does that, not how the code works.
- &#9745; There should be an explanation for any code that is commented out.
- &#9745; No hard coding, use constants/configuration values.
- &#9745; Never, ever, use a magic number/string.
- &#9745; Avoid multiple if/else blocks
- &#9745; Logging: Do not log the critical information (e.g. credit card number, SSN).Consider encrypt critical information in log if the information logging is required.
- &#9745; Remove unused code from the source file instead of commenting it out.
- &#9745; Use StringBuilder whenever multiple concatenations are required.
- &#9745; Always check Event & Delegate instances for null before invoking.
- &#9745; Do not create concrete object using "new" keyword. Use DI instead.
- &#9745; Do not put too much business logic in Controller layer. Put it in BAL layer or Stored procedure.
- &#9745; Always try to have a unit test for the new piece of code.
