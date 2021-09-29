    
    public function getCurrentWorkplace(): array
    {
        return [
           'name' => 'Rahmat AY'
           'workplace' => [
                'college' => 'Yogyakarta State University',
                'position' => 'Student'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Python::class,
            Java::class,
            C++::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'be come a developer someday.';
    }
}
