# Improvedmetrolist source recovery

This branch reconstructs normal Git-tracked Android source while leaving the known-good `main` build untouched.

Baseline: Improvedmetrolist `57f3c441c9ca8dcafd79fb77dd38d83a274431c8`, based on the Metrolist 13.6.3 source family.

Pending recovery includes recommendation injection, playlist/Media3 shuffle synchronization, queue/timeline/index crash guards, protected `No mood` aggregation, mood-store safety, and backup of moods plus per-song mood preferences/feedback.

Do not merge until the APK workflow passes.
