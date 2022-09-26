```php
<?php

namespace DaniKoehler;

class About extends Me {

    public function getWorkplace(): array {

        return [
            'workplace' => [
                'local' => 'Home Sweet Home',
                'position' => 'Backend Web Dev'
            ]
        ];
    }

    public function getKnowledge(): array {

        return [
            Php::class,
            Laravel::class,
            Javascript::class,
            Html::class,
            Css::class,
        ];
    }

    public function getFutureGoals(): array {

        return [
            'personal' => [
                'study' => 'book at least 2 hours a day',
                'games' => 'dont give up games before the end',
            ],

            'professional' => [
                'git' => 'keep my portfolios always up to date',
                'me' => 'continue evolving my knowledge'
            ]
        ];
    } 
}
```
