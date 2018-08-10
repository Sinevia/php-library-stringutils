# PHP Library String Utils #

Utility functions for working with strings

## Installation ##

```
composer require sinevia/php-library-stringutils v1.1.0
```

## Methods ##

- camelize($string, $separator = " ", $remove_separator = false)
- endsWith($string, $match) - Checks if a string ends with another string
- fixNewLines($text) - Fixes all new lines \r\n to become \n
- from_camel_case($input)
- htmlEmailToText($html) - Simple function to convert HTML email to text
- hasLowercase($string)
- hasMinumumChars($string, $chars)
- hasOnly($string, $gama) - Checks whether a string contains only characters specified in the gama.
- hasUppercase($string)
- hasNumber($string)
- hasSubstring($string, $substring)
- isEmail($email)
- leftFrom($string, $match)
- maxWords($string, $num, $suffix = '') - Returns the first $num words of $string
- p2br($string) - Converts a well-formed string with &gt;p> tags to string with &gt;br /> tags
- random($length = 8, $string = "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz1234567890") - Returns a random string.
- regexSurround($string,$regex,$prefix,$postfix) - Surrounds a matching regex with prefix and postfix string
- regexReplace($string,$regex,$replacementWithMatches) - Replaces a matching regex with match aware replacement string
- rightFrom($string, $match)
- slugify($string) - Creates a friendly URL slug from a string
- snakify($string, $separator = " ", $remove_separator = false)
- splitId($string) - Given a string such as "comment_123" or "id_57", it returns the id
- startsWith($string, $match) - Checks if a string starts with another string.
- substringBetween($string, $match_left, $match_right, $ignore_case = false)
- toWords($string) - Splits a string to words
