# Changelog

## 1.0.1 - 2026-11-12

### Changed

- Publishing moved to Maven Central via the Central Portal (OSSRH was shut down), using the
  `com.vanniktech.maven.publish` plugin. Coordinates are unchanged: `ru.kode.plexus:core`.
- Kotlin 1.9.0 -> 2.3.20, kotlinx-coroutines 1.6.4 -> 1.10.2, Gradle 8.7 -> 9.4.1.
- No public API change. Bytecode target is still JVM 11.
