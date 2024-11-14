part of [[Concurrency]]
Use case : connections
Semaphore semaphore = new Semaphore(3);
semaphore.acquire();
semaphore.release();