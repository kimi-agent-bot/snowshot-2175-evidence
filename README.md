# Snow Shot crash evidence (mg-chao/snow-apps#2175)

Evidence for https://github.com/mg-chao/snow-apps/issues/2175

- `snowshot-crash-logs.zip` — 14 WER Report.wer (snow_shot.exe 1.3.0/1.3.6/1.3.8 x13 + snow_shot_mini.exe x1), snow_shot app logs, README.txt with environment details.
- Environment: Windows 11 Pro 25H2 build 26200.9457 / RTX 4060 Ti (driver 32.0.16.1060) / GameViewer virtual display present.
- Key fields: ntdll.dll 10.0.26100.9444, exception c0000005; mini offset 0xcc6ff, full 1.3.8 offset 0x157c2; crash during d3d12/dxgi load.
- snowshot-crash-logs.zip SHA256: see issue comment.

This repository is temporary and will be removed after the issue is resolved.
