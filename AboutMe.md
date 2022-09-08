# Prasanna Boddapati
 I am Prasanna Boddapati. I am from Ongole, India. I have completed my under graduation in KITS College AndhraPradesh. After that i worked with DXC Technology as an Data Analyst in Canadian Imperial Bank of Commerce (CIBC) Project. My goal in this course is to improve my database skills and apply my knowledge to use several database frameworks where I can reach my goal of becoming a professional Data Scientist/Analyst.

 ![image](prasanna.png)
 [Link to the Image](https://github.com/boddapatiprasanna/assignment2.Prasanna/blob/main/prasanna.pn)

 ****
## Cities that are recommended to visit
|   Name of the City  |       Locations to visit       |         visiting hours           | 
|:--------------------|:------------------------------ |:---------------------------------|
|       Delhi         |  The Lotus Temple              |           7 hours                |
|      Aagra          |  Tajmahal                      |           4 hours                |
|      Varanasi       |  Holy city                     |           1 hour                 |
|      Mumbai         |  The gateway of india          |           3 hours                |

****

## Quotes 

> A person who never made a mistake never tried anything new
>
> Bombs and pistols do not make a revolution. The sword of revolution is sharpened on the whetting stone of idea by Bhagat Singh
****

## Code Fencing

> [Functional Programming Functions](https://stackoverflow.com/questions/57025743/using-function-and-if-statement-in-scss)

```
/// Apply `$function` with `$args` to each item from `$list`.
/// @author Kitty Giraudel
/// @param {List} $list - List of items
/// @param {String} $function - Function to apply to every item from `$list`
/// @param {Arglist} $args - Extra arguments to pass to `$function`
/// @return {List}
/// @throw There is no `#{$function}` function.
@function walk($list, $function, $args...) {
  @if not function-exists($function) {
    @error "There is no `#{$function}` function.";
  }
  
  @for $i from 1 through length($list) {
    $list: set-nth($list, $i, call($function, nth($list, $i), $args...));
  }
  
  @return $list;
}

```

[Code snippet](https://css-tricks.com/snippets/sass/functional-programming-functions/)
