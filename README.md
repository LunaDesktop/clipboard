# Luna Clipboard

Historia schowka środowiska Luna: ostatnie skopiowane teksty, filtr po całej
treści, przypinanie (`Ctrl+P` / gwiazdka) i wklejanie z powrotem
(`Enter` / dwuklik). Przypięte wpisy nigdy nie wypadają z historii.
Plik `~/.config/luna/clipboard.conf` ma prawa `0600`; aplikacja nie łączy się
z siecią.

## Budowanie i uruchamianie

```sh
cargo build --release --locked
cargo run --locked
cargo run --bin preview   # podglądy do docs/images
```

Wymaga kompozytora Selene. libLunę `cargo` pobiera z repozytorium
https://github.com/LunaDesktop/libLuna (w monorepo Luna są to ścieżki `../libluna`).
Więcej: `docs/clipboard.md` w monorepo Luna.
