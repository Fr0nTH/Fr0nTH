```php
<?php
namespace Ivan-Jank0vic;
class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'unemployed',
                'position' => 'layingDown'         
            ]
        ];
    }
    public function getDailyKnowledge(): array
    {
        return [
            Linux::,
            css::,
            C++::class,
            Node.js::class
        ];
    }
    public function getFutureGoal(): string
    {
        return 'To contribute to open source!';
    }
}
```
