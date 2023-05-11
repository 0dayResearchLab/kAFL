# 🌟 Features

/

# ✨ Improvements

- Upgrade kAFL kernel from `5.10.73` -> `6.0` (#178)
  - kernel base config from Ubuntu 22.04

# 🔧 Fixes

- include QEMU ROM files in Docker image (#168)
- push `intellabs/kafl:latest` tag by default (#169)
- checking `/sys/devices/cpu*/caps/pmu_name` for AlderLake CPUs (#174)

# 📖 Documentation

- use `intellabs/kafl:latest` image in documentation
- document `grimoire`  (`--grimoire`) config key (#177)

# 🧰 Behind the scenes

- deprecate NodeJSv12 based actions (#180)
- deprecate Ubuntu-18.04 runner (#181)
- deprecate set-output in Github Actions (#182)
  