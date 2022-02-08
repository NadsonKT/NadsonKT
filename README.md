<?php

namespace NadsonKT;

class About extends Me
{    
    public function getWorkplace(): array
    {
        return [
            'company'    => 'Goyan Developers',
            'position'   => 'Senior Engineer',
            'department' => 'Web application development',
        ];
    }

    public function getKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            Javascript::class,
            CodeIgniter::class,
            MySQL::class,
            React::class
        ];
    }
}
