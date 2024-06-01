# How to build a simpple Kotlin rest api as quickly as possible

1. Start in Intellij by creating a Spring boot - Maven - Kotlin project and a Spring Web dependency
2. Create a package named `controller` or `resource` and add a kotlin class file named `<name>Controller`
3. Use `@RestController` and `@RequestMapping` to annotate the class and make a function with e.g. `@GetMapping`
4. Start the application and try to execute with `curl`(http), Postman or just your browser

**Local development with Angular**

Add `@CrossOrigin(origins = ["http://localhost:4200"])` to the `RestController` class to make it function with Angular and not hit a CORS error