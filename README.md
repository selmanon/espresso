# espresso showcase

What the project do as Test ? 
Check if the `MainActivity` contain `Hello`

What the project use from the Espresso API ?
 - onView
 - check
 - ViewAssertions
 - matches
 
`onView(withText("Hello")).check(ViewAssertions.matches(isDisplayed()));`

Everything About Espresso is here : 

![alt tag](http://i1.wp.com/adventuresinqa.com/wp-content/uploads/2015/04/Espresso-Cheat-Sheet.jpg?zoom=2&resize=620%2C477)


Choose Run -> Edit configurations

 - Set the module : to app
 - Specific instrumation runner to : android.support.test.runner.AndroidJUnitRunner (the same you set on build.gradle)

![alt tag](https://github.com/selmanon/espresso/blob/master/screenshots/runtestconfig.png)

Espresso Test Result

![alt tag](https://github.com/selmanon/espresso/blob/master/screenshots/espressotestresult.png)
