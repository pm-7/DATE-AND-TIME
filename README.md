# DATE-AND-TIME

• Fluent API
• Immutable instances
• Thread safe
• Strong types
• Fit for purpose types

• Not Fluent
• Mutable instances – clone needed
• Not Thread safe
• Weakly typed calendars
• One size fits all API

10

Classical Date Time API Classes
The primary classes before Java 8 release were:

Java.lang.System: The class provides the currentTimeMillis() method that returns the current time in milliseconds. It shows the current date and time in milliseconds from January 1st 1970.

java.util.Date: It is used to show specific instant of time, with unit of millisecond.

java.util.Calendar: It is an abstract class that provides methods for converting between instances and manipulating the calendar fields in different ways.

java.text.SimpleDateFormat: It is a class that is used to format and parse the dates in a predefined manner or user defined pattern.

java.util.TimeZone: It represents a time zone offset, and also figures out daylight savings.
