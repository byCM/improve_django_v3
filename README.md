## Improve a Django Project <br />

### Instructions ###


We spent a weekend doing a hackathon a year or so ago and someone built this project. It's...not the best. It runs kind of slow and has been a real pain to debug and add onto. We need you to go through the project, find where it's inefficient, and fix it. Check the templates for bad inheritance and extra database calls. Check the views for extra views or extra database calls. Check the models to make sure they're using the best fields. Check the forms for proper validation and fields. Basically just check the whole thing over. Oh, and it doesn't have any tests, so please get test coverage up to at least 75% <br />
<br />
>- No view has more than 5 queries. Queries take less than 100ms combined. <br />
>- Templates inherit nicely to reduce the total amount of code written. <br />
>- Model fields are corrected to store correct value types. Migrations are included to change the field types.<br />
>- Form validation is corrected for proper use of clean(), clean_field(), and validators. <br />
>- Test coverage is at or above 75%. <br />
>- The code is clean, readable, and well organized. It complies with most common PEP 8 standards of style. <br />


