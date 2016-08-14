# Coding guidelines
The rules and good practices to abide by while coding in Raiffeisen Solutions

## Dates and time
* One shall not use ~~`java.util.Date`~~ and ~~`java.util.Calendar`~~. These classes are so full of errors that are considered to be going to be completely deprecated in Java 9.
* In lieu of ~~`Date`~~ and ~~`Calendar`~~ we should use **`Instant`** and **`LocalDateTime`** respectively
* Use `LocalDate`, `LocalTime` and `LocalDateTime` only when the place in the world is not important. When it's important, use **`ZonedDate`**, **`ZonedTime`** and **`ZonedDateTime`** respectively
