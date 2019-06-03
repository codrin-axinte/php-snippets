# PHP Snippets

Helpful code blocks for PHP/Laravel.

```php
 /**
   * Replaces an amount of characters with a placeholder
   * Example: 
   * Usage: string_protect('07716 1234', 3)
   * Output: 07716 1XXX
   * @param int $chars
   * @param string $placeholder
   * @return string
   */
function string_protect($string, $length = 4, $placeholder = 'X') {
   return substr_replace(
          $string,
          str_repeat($placeholder, $length),
          -$length
      ); 
}
```
