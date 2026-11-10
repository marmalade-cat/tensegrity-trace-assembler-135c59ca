TensegrityTraceAssembler

Small prototype: normalize per-module pose/orientation time-series (CSV or JSON) into a common schema and replay on a simple handheld tensegrity mockup.

Usage: open index.html in a browser. Two sample modules are included (one CSV, one JSON). The Normalizer validates timestamps, linearly resamples to a common frame rate, and outputs a unified trace for replay.

Notes: No network or filesystem access. This is an example prototype; adapt parsing and validation for real datasets.