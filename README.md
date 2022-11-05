# Tests
JUnit, mockito

## Unit Tests
Are written for single software parts. Typically one unit test in Java verifies one class method.

## Mocking Frameworks
- Mockito
- JMockit
- EasyMock

## What should be mocked?

![alt text](https://github.com/DeltaRig/Tests/blob/main/class+diagram.png.jpg?raw=true)

## Notations about test

@BeforeEach and @AfterEach

@MockBean to replace beans with mocked beans.

@Test to determine that the next _method_ is a test

@Autowired provides control over where and how binding between beans should be performed. Can be used to in setter methods, in the constructor, in a _property_ or methods with arbitrary names and/or multiple arguments.

@SpringBootTest to determine that this _class_ is a Class test of SpringBoot, the test with this annotation will take much longer to execute then a simple unit test. Is used to integration tests.

@SpyBean to create a spy bean instante