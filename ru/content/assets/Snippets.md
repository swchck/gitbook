# Snippets

## Simple Exercise

{% exercise %}
Define a variable `x` equal to 10.

{% initial %}
var x =

{% solution %}
var x = 10;

{% validation %}
assert(x == 10);

{% context %}
// This is context code available everywhere
// The user will be able to evaluate `exposedVar`
//var exposedVar = 3;
// ... or call `exposedFunction`
//function exposedFunction {
//    return 3;
//}
{% endexercise %}

## Embeded Github Gist

{% gist id="https://gist.github.com/SamyPesse/6ceb8cb8d531ffab75f0" %}{% endgist %}

## Embeded Hints

{% hint style='info' %}
Important info: this note needs to be highlighted
{% endhint %}
{% hint style='tip' %}
Important info: this note needs to be highlighted
{% endhint %}
{% hint style='danger' %}
Important info: this note needs to be highlighted
{% endhint %}
{% hint style='working' %}
Important info: this note needs to be highlighted
{% endhint %}

## Simple Table

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

## Embeded YouTube Video

{% youtube src="https://www.youtube.com/watch?v=9bZkp7q19f0" %}{% endyoutube %}
