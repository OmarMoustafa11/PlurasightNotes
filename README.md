# PlurasightNotes
Test is just code Executes target code Benefits of unit testing 
-Quick feedback
-Automated regression checking

BENEFITS OF UNIT TEST
Quicker feedback,Automated regression checking(or tests), design aid (allows to see if code is understandable), improves confidence, documentation (u can tell wat a class does from the test class)

tests are important to show how a class can work. 

Design aid 
-Improves confidence
-Form of documentation

If you use an assertEquals to compare collections Unit will check that the two collections contain equivalent objects
using the equals method on those objects and those objects are in the same order

A method annotated with BeforeAll will run once before all test methods in the class

A beforeEach annotated method will run once before each test method

An afterEach will run once after each test method

An AfterAll annotated method will run once after all tests in the class have completed

After All and BeforeAll are at the class level and so are static

JUnit 5 provides a DisplayName annotation that allows us to specify the text it'll use to build a report instead of the
class and method names.

Some JUnit Annotations

@Test @DisplayName @BeforeEach @AfterEach @BeforeAll

Some JUnit Assertions

assertEquals assertFalse assertNull assertAll assertTrue

To temporarily siable a unit test from running you use the diabled annotation in Junit 5.

Junit provides a mechansim that gives us the ability to tage test classes and test methods and excute test by tag
expressions

Dependencies -Code rarely works in isolation-code calls other code -Such dependecnies may be application code or
libary code -Testing code that calls other code can be difficult
Test-driven Development - Rather than implemting a feature first, then testing it, drive development of the feature from a test
