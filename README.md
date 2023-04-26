```php
<?php

namespace DaniKoehler;

class About extends Me
{
    /**
     * @return Array
     */
    public function getWorkplace(): Array
    {
        return [
            'workplace'    => [
                'local'    => 'Home Sweet Home',
                'position' => 'FullStack Web Developer'
            ]
        ];
    }

    /**
     * Knowledge I'm improving every day
     * @return Array
     */
    public function getKnowledge(): Array
    {
        return [
            Php::class,
            Laravel::class,
            Javascript::class,
            JQuery::class,
            Html::class,
            Css::class,
            Docker::class,
            MySQL::class,
            Oracle::class,
            MongoDB::class,
            PHPUnit::class,
            RestAPI::class
        ];
    }
    
    /**
     * @return Array
     */
    public function getFutureGoals(): Array
    {
        return [
            'personal'  => [
                'study' => 'Book at least 2 hours a day.',
                'games' => 'Don't give up games before the end.',
            ],

            'professional' => [
                'company'  => 'Start my own company.'
            ]
        ];
    }
    
    /**
     * @return Array
     */
    public function getHowToReachMe(): Array
    {
        return [
            'contact'      => [
                'gmail'    => 'ntckoehler@gmail.com',
                'linkedin' => 'https://www.linkedin.com/in/danikoehler/'
            ]
        ];
    }
}
```
