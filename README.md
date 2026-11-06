# 🎬 Media & Torrent Hub

Curated links — movies, series, anime and torrent tooling. Repo links verified live (★ counts, Nov 2026); site reachability tested from my machine (India ISP) — ⚠️ = blocked locally, use VPN/proxy.

## Torrent clients & search
| Link | What it is |
|------|-----------|
| [qbittorrent/qBittorrent](https://github.com/qbittorrent/qBittorrent) | The Qt torrent client with search plugins + RSS |
| [Jackett/Jackett](https://github.com/Jackett/Jackett) | Indexer proxy — unify hundreds of trackers into one API |
| [FlareSolverr/FlareSolverr](https://github.com/FlareSolverr/FlareSolverr) | Cloudflare bypass proxy for Jackett/*arr |
| [melqtx/tork](https://github.com/melqtx/tork) | TUI torrent search+client (Knaben/YTS/Nyaa …), built-in Tor mode |
| [YueMiyuki/Risuko](https://github.com/YueMiyuki/Risuko) | Motrix revival — HTTP/FTP/BT downloader (Tauri) |
| [anefzaoui/misterdownloadmanager](https://github.com/anefzaoui/misterdownloadmanager) | Clean-room download manager (HTTP/video/torrent) |

## Movies & series automation (*arr stack)
| Link | What it is |
|------|-----------|
| [Radarr/Radarr](https://github.com/Radarr/Radarr) | Movie library automation (search/grpc/process) |
| [Sonarr/Sonarr](https://github.com/Sonarr/Sonarr) | TV series automation |
| [Prowlarr/Prowlarr](https://github.com/Prowlarr/Prowlarr) | Indexer manager feeding Radarr/Sonarr (successor to Jackett for *arr) |
| [morpheus65535/bazarr](https://github.com/morpheus65535/bazarr) | Auto subtitles companion for Radarr/Sonarr |
| [seerr-team/seerr](https://github.com/seerr-team/seerr) | Request & discovery manager for Jellyfin/Plex/Emby |
| [Jackett's indexer status](https://github.com/Jackett/Jackett/blob/master/src/Jackett.Server/Definitions/IndexerDefinitions.cs) | What trackers Jackett maintains right now |

## Sites (indexers / search engines)
| Site | Reachable (my ISP, 2026-11) |
|------|------------------------------|
| [nyaa.si](https://nyaa.si) | ✅ anime source of truth |
| [knaben.org](https://knaben.org) | ✅ meta search engine (knaben.eu → redirects/blocked) |
| [btdig.com](https://btdig.com) | ✅ DHT crawler search |
| [torrentio.strem.fun](https://torrentio.strem.fun) | ✅ Torrentio — Stremio's torrent provider + config portal |
| [yts.mx](https://yts.mx) | ⚠️ movies (angleblocks small sizes) — VPN here |
| [1337x.to](https://1337x.to) | ⚠️ general index — VPN here |

## Streaming / Stremio ecosystem
| Link | What it is |
|------|-----------|
| [Stremio/stremio-web](https://github.com/Stremio/stremio-web) | Streaming + plugins client |
| [Stremio Addons catalog](https://github.com/Stremio/stremio-addons) | Official addon ecosystem list (Torrentio, subtitles, …) |
| [5rahim/seanime](https://github.com/5rahim/seanime) | Anime media server (torrent streaming + local) |
| [aniyomiorg/aniyomi](https://github.com/aniyomiorg/aniyomi) | Android anime & manga app |
| [hydralauncher/hydra](https://github.com/hydralauncher/hydra) | Game launcher w/ torrent-based DRM-free sourcing |

## My stack notes
Self-hosted: Jackett (systemd, /opt/Jackett) + qBittorrent 5.3 (jackettdedup + jackett.json search plugins) · MDM/MDM-cli + tork CLI · Risuko app. Checked via `tork doctor`: Knaben ✓ Nyaa ✓.
