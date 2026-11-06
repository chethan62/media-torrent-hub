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

## TV & viewing apps (from GitHub trending, vetted 2026-11)
| Link | What it is | ★ |
|------|-----------|---|
| [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) | Debloat any Android/Google TV over Wi-Fi, Apple-TV-style home | 53k |
| [simbasjungles/free-my-tv](https://github.com/simbasjungles/free-my-tv) | Ad-free home screen for Google TV/webOS/Tizen, one-button undo | 6k |
| [man15h/tellyscope](https://github.com/man15h/tellyscope) | Debloat/install/browse Android TV from your phone, no root | 1.6k |
| [Ansub/tv-detox](https://github.com/Ansub/tv-detox) | Claude/Codex-driven TV clean-up prompt + tiny home screen | 2.2k |
| [humblemuzzu/dumbtv](https://github.com/humblemuzzu/dumbtv) | Fire TV declutter over ADB, reversible, with own home screen | 2k |
| [xMazaki/unbloat-android-tv](https://github.com/xMazaki/unbloat-android-tv) | Slim Android TV, reversible double-click | 0.3k |
| [Seagey/couch-tv](https://github.com/Seagey/couch-tv) | Own Google TV home + phone remote (+optional Claude) | 0.2k |
| [piermark/omarchytv](https://github.com/piermark/omarchytv) | Omarchy-style launcher ecosystem across TV/phone/desktop | 0.5k |
| [aradhyas8/Plume_Launcher](https://github.com/aradhyas8/Plume_Launcher) | 0.4 MB ad-free Android TV launcher | 0.3k |

## AI video creation & editing (agents)
| Link | What it is | ★ |
|------|-----------|---|
| [openfilm/openfilm](https://github.com/openfilm/openfilm) | Turn any coding agent into a video agent + editor | 5k |
| [academa-labs/manimgx](https://github.com/academa-labs/manimgx) | Manim-compatible math/3D video engine on Rust GPU core | 2.6k |
| [soumatheusgomes/editonny](https://github.com/soumatheusgomes/editonny) | Local video editing through conversation | 0.8k |
| [appariciojunior/video-editor-skills](https://github.com/appariciojunior/video-editor-skills) | Claude-first-pass editing in DaVinci Resolve (CC BY-NC) | 0.4k |
| [win4r/video-director](https://github.com/win4r/video-director) | Skill: direct/verify code-rendered videos (HTML→MP4) | 0.4k |
| [sitor-ai/frametell](https://github.com/sitor-ai/frametell) | AI director agent → explainer videos, local-first | 0.5k |
| [petergyang/video-short](https://github.com/petergyang/video-short) | Raw recording → polished short with agent | 0.2k |
| [0xS4N4TG/kinetograph](https://github.com/0xS4N4TG/kinetograph) | Programmatic video engine for agents | 0.5k |

## Raw collections
- [docs/githubawesome-trending-2026-10.md](docs/githubawesome-trending-2026-10.md) — full GitHub-Trending lists (Oct 2026, ~480 rows) as captured; only the media/TV/video picks above were vetted, treat the rest as unverified.

## Terminal & CLI streaming
| Link | What it is | ★ |
|------|-----------|---|
| [mov-cli/mov-cli](https://github.com/mov-cli/mov-cli) | Watch movies/series from your terminal (plugin ecosystem) | 1.3k |
| [pystardust/ani-cli](https://github.com/pystardust/ani-cli) | The classic CLI anime scrapper → mpv | 14k |
| [sdaqo/anipy-cli](https://github.com/sdaqo/anipy-cli) | Anime in terminal, watch + download, history & profiles | 0.5k |
| [webtorrent/webtorrent-cli](https://github.com/webtorrent/webtorrent-cli) | Stream torrents in your player over BitTorrent | 1.4k |
| [mafintosh/peerflix](https://github.com/mafintosh/peerflix) | The original streaming-torrent-to-VLC/mpv CLI | 6.3k |
| [streamlink/streamlink](https://github.com/streamlink/streamlink) | Pipe live streams (YouTube/Twitch/…) into any player | 12k |
| [mps-youtube/yewtube](https://github.com/mps-youtube/yewtube) | Terminal YouTube player/download, no API key | 8.8k |
| [yt-dlp/yt-dlp](https://github.com/yt-dlp/yt-dlp) | The downloader everything depends on | 206k |
| [Aanok/jftui](https://github.com/Aanok/jftui) | Jellyfin server in your terminal | 0.2k |
| [mpv-player/mpv](https://github.com/mpv-player/mpv) | The player all of the above pipe into | 38k |
| [mesamirh/MovieBox-Tui](https://github.com/mesamirh/MovieBox-Tui) | Find, download & stream movies/TV/live TV in a TUI — kitty/Sixel poster art, resume & library, local-only, prebuilt Linux x64 in Releases | 2.8k |
