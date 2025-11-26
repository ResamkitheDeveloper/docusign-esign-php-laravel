## Compatibility update for guzzle >=7.10.0, docusign/esign-client >=8.5.0 and php >=8.2
# Docusign eSign PHP Laravel
A Laravel wrapper for the [DocuSign eSign PHP Client](https://github.com/docusign/docusign-esign-php-client)

### To use this add the following to your composer.json file

```
"repositories": [
  {
    "type": "vcs",
    "url": "https://github.com/ResamkitheDeveloper/docusign-esign-php-laravel"
  }
],
```
```
"require": {
  "docusign/esign-laravel": "dev-main",
}
```
### Then run this in terminal while in project directory
```
composer update docusign/esign-laravel --with-all-dependencies
```
Add the service provider to the `providers` array in `config/app.php`

```php
DocuSign\eSign\ESignServiceProvider::class
```

## Usage
For usage see the [DocuSign eSign PHP Client](https://github.com/docusign/docusign-esign-php-client)

### Using the `DocuSign\eSign\Client\ApiClient` class
You can create a new instance of the DocuSign Client with:
```php
$client = new DocuSign\eSign\Client\ApiClient;
```
