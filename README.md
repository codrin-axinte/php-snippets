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

## Packages:
### Laravel
- [Recaptcha](https://laravel-recaptcha-docs.biscolab.com/docs/how-to-use-v2)
- [Translations Manager](https://github.com/barryvdh/laravel-translation-manager)
- [Statuses](https://github.com/spatie/laravel-model-status)
- [Currency](https://github.com/Torann/laravel-currency): Don't need this one if the countries package is used
- [GeoIP](https://github.com/Torann/laravel-geoip)
- [ActivityLogger](https://github.com/spatie/laravel-activitylog)
- [Countries](https://github.com/antonioribeiro/countries-laravel)
- [Ban](https://github.com/cybercog/laravel-ban)
- [Email Confirmation](https://github.com/beyondcode/laravel-confirm-email): Deprecated: if upgraded to 5.7, use the built-in functionality
- [Campaign](https://laravel-news.com/laravel-campaign-monitor)
- [Text Avatars](https://github.com/laravolt/avatar)
- [Query Builder(Good for API Filters)](https://github.com/spatie/laravel-query-builder)
- [Breadcrumbs](https://laravel-news.com/laravel-breadcrumbs-package)
- [Count Models](https://github.com/awssat/laravel-visits): Depends on Redis
- [FireBase](https://github.com/brozot/Laravel-FCM) 
- [FireBase Notification](https://github.com/benwilkins/laravel-fcm-notification)
- [Cache](https://github.com/spatie/laravel-responsecache)
- [ElasticSearch](https://github.com/cviebrock/laravel-elasticsearch)
- [Messenger](https://github.com/cmgmyr/laravel-messenger)
- [Invoice Package](https://github.com/faustbrian/Laravel-Invoice)

### VueJs
- Vue Translations : https://github.com/kirschbaum-development/laravel-translations-loader
- Vue Pagination : https://github.com/gilbitron/laravel-vue-pagination

## Utils
 - Relationships 101: https://hackernoon.com/eloquent-relationships-cheat-sheet-5155498c209
