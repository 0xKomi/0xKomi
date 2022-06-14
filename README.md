```php
<?php

namespace Komi;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Shithook',
                'position' => 'Co-Founder'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Cpp::class,
            Javascript::class,
            Csharp::class,
            Python::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'money.';
    }
}
```
