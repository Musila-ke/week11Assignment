
This widget uses variables to store pods, bookings, and counters (e.g., arrays, strings, numbers). 
Control structures like if/else handle rule validation and flow logic. Loops (for) render the table, 
scan bookings, and compute insights like busiest hour and fill-rate. All logic is split into 
clear, single-purpose functions (e.g., parseStudentIds, findBooking, recomputeInsights). 
Events are handled via addEventListener for both form submission and table button clicks, 
enabling dynamic interactivity. DOM manipulation is used throughout: populating the pod dropdown, 
updating the bookings table, inserting/removing elements, and displaying validation errors 
and real-time insights. Strict equality (===) is used to prevent type coercion. The code avoids 
any libraries or advanced syntax, staying true to fundamentals for clarity and compatibility.
