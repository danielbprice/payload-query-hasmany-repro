
This commit shows the buggy behavior under payload 3.80.0:

- Install
- Fire up with 'npm run dev'
- Add a "Thing" "Thing1" and add a tag "Tag1" to "Thing1"
- Go to Things filter view and observe filtering by tags with the "equals" operator generating tracebacks in the query code.


---
The previous commit shows the correct behavior under payload 3.61.1.

- Install
- Fire up with 'npm run dev'
- Add a "Thing" "Thing1" and add a tag "Tag1" to "Thing1"
- Go to Things filter view and observe filtering by tags working properly without crashes
