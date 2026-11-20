# ONE CLICK — System Optimizer

A Windows 11 one-click system optimizer with a neon HUD.

## What it does

- Creates and activates the **chapo power** plan (CPU boost, no sleep, no throttling)
- Disables core parking, enables HAGS, tunes game mode / DVR
- Optimizes network stack (Nagle off, DNS, RSS, TCP settings)
- Minimizes visual effects, telemetry and background noise
- Cleans temp files, prefetch, update cache and recycle bin
- Verifies every applied setting and logs results with timings
- Monitors running games and raises their process priority

## Usage

1. Run `one click optimizer public.exe` as administrator (UAC → Yes).
2. Click **START OPTIMIZATION** in the HUD.
3. Watch the live actions and the progress ring.

## Notes

- This build contains **no data collection, no webhook and no report upload**.
- The executable stays installed after the run; it does not delete itself.
- A registry backup and a system restore point are created before tuning.
