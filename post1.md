# Post 1

just to test it.

```
@RestController
@RequestMapping("/persons")
public class PersonsController {
    private PersonService personService;
    static Comparator<Person> COMPARATOR_BY_ID = Comparator.comparing(Person::getId);
}
```
