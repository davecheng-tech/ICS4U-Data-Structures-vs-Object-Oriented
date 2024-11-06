# Designing Solutions with Data Structures and Objects

We've learned several ways to handle data and properties when designing solutions with Java. Here is a set of scenarios that require selecting an appropriate data structure among `HashMap`, `Array`, `ArrayList`, and `List`. In some cases, a different approach such as creating a dedicated class may be more suitable.

## Scenarios

### Scenario 1: Company Employee Directory
A company wants to create an employee directory where each employee can be looked up by their unique ID to access details like name, position, and contact information.

**Question**: Which data structure would you use to store employee information and why? Could a different design, such as creating an `Employee` class, be more effective?

<br>

### Scenario 2: Student Attendance Tracker
A teacher wants to record daily attendance for students. Each student has an ID, and for each day, the teacher marks students as "Present" or "Absent."

**Question**: Which data structure would best handle this attendance tracking for multiple students over several days? Would using an `ArrayList` be effective, or could an object-oriented approach with a `Student` class be more efficient?

<br>

### Scenario 3: Social Media Follower Count
A social media application needs to keep track of how many followers each user has, allowing quick lookup of follower counts by username.

**Question**: What data structure would you use to store follower counts, and why? Would a `HashMap` be appropriate for this, or would encapsulating user data in a `User` class make more sense?

<br>

### Scenario 4: Classroom Seating Chart
In a classroom, each seat is assigned to a specific student. The seating chart must quickly show who is seated in each position, allowing changes if students need to move seats.

**Question**: What data structure would you choose to represent this seating chart? Consider if an `Array` (for fixed positions) would be sufficient, or if you might need an object-oriented `Seat` class.

<br>

### Scenario 5: Survey Response Collection
An organization conducts a survey, collecting responses to multiple-choice questions from thousands of participants. They want to store each participant’s answers and analyze trends.

**Question**: Which data structure could manage these survey responses? Would an `ArrayList` be effective for storing each participant’s answers, or would it be better to create a `Participant` class that encapsulates answers and demographics?

<br>

### Scenario 6: Online Store Product Categories
An online store needs to categorize products by type (e.g., electronics, clothing, books), where each category contains multiple products. It should allow quick retrieval of all products in a specific category.

**Question**: Which data structure would best organize products within categories? Would a `HashMap` of `ArrayLists` be suitable, or should each category be encapsulated within a `Category` class containing products?

<br>

### Scenario 7: City Bus Schedule
A public transit system wants to store the schedule for each bus route, listing stops in the order they are visited. The schedule should allow quick retrieval of all stops on a specific route and allow modifications.

**Question**: Which data structure would best store the stops for each route? Could a `HashMap` with a `List` for each route’s stops work, or would a `Route` class encapsulating stops be better?

<br>

### Scenario 8: E-commerce Order Management
An e-commerce platform needs to track customer orders. Each order includes details like item IDs, quantities, and prices. Orders should be quickly searchable by order ID.

**Question**: Which data structure would best manage orders? Is a `HashMap` suitable for this, or would it be more practical to create an `Order` class to encapsulate order details?

<br>

### Scenario 9: Leaderboard for a Video Game
A video game tracks player scores, showing a leaderboard that ranks players by score. The leaderboard needs to be updated frequently, with players moving up and down based on score changes.

**Question**: Which data structure would you use to store player scores? Would a `List` of scores work, or would a `Player` class be more efficient for handling complex ranking logic?

<br>

### Scenario 10: Warehouse Inventory Tracking
A warehouse needs to manage inventory items. Each item has a name, SKU, and stock level. Warehouse workers frequently need to look up items by SKU and update stock levels.

**Question**: Which data structure would be best for managing warehouse inventory? Would a `HashMap` of SKUs to stock levels be appropriate, or would an `Item` class encapsulating details be more effective?
