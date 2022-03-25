# nova-registerpage

## Installation

Update the composer.json file in the root of your laravel (nova) project:
 
`composer config repositories.nova-registerpage '{"type": "vcs", "url":"https://github.com/acvxqs/nova-registerpage"}' --file composer.json`

Install the package:

`composer require acvxqs/nova-registerpage`

Go to your `/nova/register` page to view the registration screen.

## Configuration

By default (after installation) the page `/nova/register` is enabled and will show.

Use the command `php artisan vendor:publish --tag="nova-registerpage"` to publish the configuration file. Doing so, will _disable_ the `/nova/register` page as the config paramater is set to _false_

## Note

Never done anything like this before. Feedback appreciated. 
