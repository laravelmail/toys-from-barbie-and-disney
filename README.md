# Toys From Barbie And Disney

Professional marketing email highlighting new toys from Barbie and Disney.

![Thumbnail](./thumbnail.png)

## Template Details

- **Industries:** Entertainment
- **Message Type:** Marketing
- **Tags:** promotion, toys, barbie, disney

## Files
- `index.html`: The improved, localized, and branded HTML template.
- `template.blade.php`: Ready-to-use Laravel Blade template with `asset()` helpers.
- `assets/`: Directory containing localized images and styles used in the template.

## Usage in Laravel

### 1. Store the Template
Place the `index.html` content in a Blade view (e.g., `resources/views/emails/toys-from-barbie-and-disney.blade.php`).

### 2. Handle Assets
Move the content of `assets/` to your public directory (e.g., `public/vendor/mail-templates/toys-from-barbie-and-disney/`) and update the paths in the HTML to use the `asset()` helper.

### 3. Send Email
```php
Mail::to($user)->send(new \App\Mail\GenericEmail([
    'view' => 'emails.toys-from-barbie-and-disney',
    'data' => [
        // Your dynamic data here
    ]
]));
```

---
*Created with ❤️ by **[LaravelMail.com](https://laravelmail.com)** - Your source for professional email templates.*
