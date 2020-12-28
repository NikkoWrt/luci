<p align="center">
<img src="/logo.png" alt="NikkoWrt" width="100">
</p>
<h1 align="center">NikkoWrt</h1>

> 🥓 Nikko luci feed Base on [OpenWrt](https://openwrt.org/)


## Usage

This feed is enabled by default. Your feeds.conf.default (or feeds.conf) should contain a line like:
```bash
src-git luci https://github.com/nikkowrt/luci.git
```

To install all its package definitions, run:
```bash
./scripts/feeds update luci
./scripts/feeds install -a -p luci
```

## License

See [LICENSE](LICENSE) file.
 
## Package Guidelines

See [CONTRIBUTING.md](CONTRIBUTING.md) file.
