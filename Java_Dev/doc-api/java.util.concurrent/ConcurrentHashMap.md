## `java.util.concurrent.ConcurrentHashMap<K,V>`

一个哈希表，支持完全并发的检索和可调的更新预期并发。此类遵循与哈希表相同的功能规范，并包含与哈希表的每个方法对应的方法版本。然而，即使所有操作都是线程安全的，检索操作也不需要锁定，并且没有任何支持以阻止所有访问的方式锁定整个表。在依赖线程安全而不依赖于同步细节的程序中，此类与哈希表完全可互操作。