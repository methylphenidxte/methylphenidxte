```php
<?php

namespace Methylphenidxte;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'KIMIA FARMA',
                'position' => 'Founder'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Angular::class,
            ReactNative::class,
            TailwindCss::class,
            Aws::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
