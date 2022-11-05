NUID: 002790368
Name: Prarthna Nemade

Assignment 7--------->
-------------------------------------------------------------------------------------------------
1.  CSS Grid box:
  The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, 
  making it easier to design web pages without having to use floats and positioning.
  I have used the CSS grid layout to display iamges.

2.  CSS Felx box:
  The Flexbox Layout module aims at providing a more efficient way to lay out, align and distribute 
  space among items in a container, even when their size is unknown and/or dynamic.
  I have used the CSS flex layout to display iamges.

3.  Variables in SCSS:
  Sass variables are that you assign a value to a name that begins with $, and then you can refer
  to that name instead of the value itself.
  Variables used: 
$light: #68b578;
$dark: #1f5c28;
$lime: #89e632;
$orangeRed: #767373;
$blue: #bc1212;

$gradientColor1: #560bad;
$gradeintColor2: #8e60c4;
$formBackgroundColor: #300169;
$pinkOutline: #a31a6a;
$loginButtonColor: rgb(96, 196, 96);
$loginButtonTextColor: white;
$newAccountButtonColor: #ffd60a;
$newAccountButtonTextColor: rgb(36, 34, 34);
$inputBackgroundColor: #2b045c;
$inputPlaceholderColor: rgba(255, 255, 255, 0.548);
$loginWithAccountsTextColor: white;
$inputTextColor: white;
$forgetHoverColor: white;

$name: "/images/bg.jpg";

4.  Custom Properties:
  A custom property is most commonly thought of as a variable in CSS.
  custom properties used:
  
5.  Nesting:
  Nesting is combining of different logic structures. 
  Using SASS, we can combine multiple CSS rules within one another. 
  nav {
  ul {
    margin: 0;
    padding: 0;
    list-style: none;
  }
  li {
    display: inline-block;
  }
  a {
    display: block;
    padding: 6px 12px;
    text-decoration: none;
  }
}
  Notice that in Sass, the ul, li, and a selectors are nested inside the nav selector.
  While in CSS, the rules are defined one by one (not nested).
  I have nested telephone number and email.

6.  Interpolation:
  It provides SassScript variables in selectors and property names using #{ } syntax.
  You can specify variables or property names within the curly braces.
  I have used interpolation to display contents.
  p:after {
   content:  #{1 + 2};
  }

7.  Placeholder selectors:
  Placeholder is another special kind of selector. It is used when you are writing your own SASS library. 
  Its work is very similar to mixin without arguments.
  Placeholder selector starts with a % sign.
  I have used placeholder to create a button.

8.  Mixins:
  Mixins are a language concept that allows a programmer to inject some code into a class.
  I have used mixins in a login form.

9.  Functions:
  Functions allow you to define complex operations on SassScript values that you can re-use throughout your stylesheet. 
  I have decalred a function to print some statements.
$first-width: 5px;
$second-width: 5px;

@function adjust_width($n) {
   @return $n * $first-width + ($n - 1) * $second-width;
}
#set_width { padding-left: adjust_width(10); }

