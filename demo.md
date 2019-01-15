```
	/**
	 * Creates an instance of {@code ReentrantLock}.
	 * This is equivalent to using {@code ReentrantLock(false)}.
     */
	public ReentrantLock() {
    	sync = new NonfairSync();
	}
```
