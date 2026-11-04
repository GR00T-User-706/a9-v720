# A9 V720 Camera Research Standards

This repository documents and experiments with communication and control behavior for a specific A9/V720/Naxclow camera family. The README currently identifies camera firmware/version `202212011602` as the tested target. Do not generalize that result to other hardware revisions or firmware.

## Evidence and protocol claims

Separate observed packet captures, reverse-engineered behavior, hypotheses, and unverified assumptions. Record capture conditions, camera model/firmware, application mode, network topology, timestamps, and tool versions where known. Preserve original captures and label derived or sanitized copies.

Do not present inferred protocol fields, endpoints, authentication behavior, or command effects as confirmed until supported by reproducible observations.

## Safety and privacy

Treat camera credentials, network identifiers, video files, and packet captures as sensitive. Document where recordings and captures are stored and how to avoid exposing them in logs or public examples. Warn users about connecting the device to untrusted networks and about possible vendor update traffic only where supported by evidence.

## Script documentation

For each command-line script, document syntax, options, defaults, output paths, network actions, failure behavior, and camera state changes. Distinguish AP and station modes and explain when operations pause recording or otherwise affect device behavior.

## Compatibility and testing

Record tested camera hardware and firmware separately from untested targets. A successful connection to one device is not proof of compatibility with the product family. Separate static inspection, replay against captures, tests on a controlled local network, and tests against physical hardware.
