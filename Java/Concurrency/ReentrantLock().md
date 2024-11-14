part of [[Concurrency]]

kinda the same as [[synchronized]]


Lock lock = new ReentrantLock();
lock.lock() - could be used N times
lock.unlock() - should be invoke as many times as corresponding lock()