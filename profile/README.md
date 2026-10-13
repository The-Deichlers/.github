<p align="center">
  <img src="https://raw.githubusercontent.com/The-Deichlers/.github/main/profile/assets/the-deichlers-crest.jpg" alt="The Deichlers family crest" width="220" />
</p>

<h1 align="center">The Deichlers</h1>

<p align="center">
  <strong>A connected home. A world to explore. Built with care.</strong><br />
  Two connected priorities: the complete Northrend gaming platform and our home infrastructure.
</p>

<p align="center">
  <a href="#northrend-platform"><strong>Northrend Platform</strong></a>
  &nbsp;|&nbsp;
  <a href="#home-infrastructure"><strong>Home Infrastructure</strong></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/orgs/The-Deichlers/repositories">Explore our repositories</a>
</p>

---

## Northrend Platform

Our family-and-friends World of Warcraft platform is more than a launcher:
**AzerothCore, Playerbots, custom server modules, the web portal, client addons,
and Windows, macOS, and Linux launchers form one connected product.**

Northrend brings together bot-assisted dungeon and raid play, ARC communication,
live world maps, raid reports, account and character tools, and managed client
and addon delivery. Source, build definitions, integration contracts, and
operations are version-controlled together across the platform's repositories.

### Server, Portal, and Integration

| Component | Repository | Purpose |
|---|---|---|
| **AzerothCore** | [Northrend core](https://github.com/The-Deichlers/azerothcore-wotlk-northrend) | The game server and shared server API baseline |
| **Playerbots** | [Northrend Playerbots](https://github.com/The-Deichlers/mod-playerbots-northrend) | Bot gameplay and intentional Northrend behavior |
| **Web portal** | [Northrend portal](https://github.com/The-Deichlers/acore-portal-northrend) | Character and account tools, raid planning, reports, live maps, browser play, and administration |
| **Reproducible stack** | [Server build](https://github.com/The-Deichlers/northrend-server-build) | Exact component revisions and complete server builds |
| **Operations** | [Server operations](https://github.com/The-Deichlers/northrend-server-operations) | Deployment, maintenance, backups, and rollback |
| **Shared contracts** | [Integration specs](https://github.com/The-Deichlers/northrend-integration-specs) | Interfaces between server, portal, addons, and launchers |

### Server Modules

| Area | Repositories |
|---|---|
| **ARC and portal integration** | [Portal Tools](https://github.com/The-Deichlers/mod-acore-portal-tools-northrend), [MultiBot Bridge](https://github.com/The-Deichlers/mod-multibot-bridge-northrend), [Northrend Tools](https://github.com/The-Deichlers/mod-northrend-tools) |
| **Dungeon gameplay** | [Dungeon Clear](https://github.com/The-Deichlers/mod-dungeon-clear-northrend) |
| **World telemetry** | [Live Map](https://github.com/The-Deichlers/mod-live-map-northrend) |
| **Economy and customization** | [AHBot](https://github.com/The-Deichlers/mod-ah-bot-northrend), [Transmog](https://github.com/The-Deichlers/mod-transmog-northrend), [Rental Mounts](https://github.com/The-Deichlers/mod-rental-mounts-northrend) |
| **Test-only development** | [ARC test harness](https://github.com/The-Deichlers/mod-arc-test-harness-northrend) - not a production module |

### Launchers and Addons

The launchers are companion applications for the platform, not the whole project:
[Windows](https://github.com/The-Deichlers/northrend-launcher),
[macOS](https://github.com/The-Deichlers/Northrend-Launcher-Mac), and
[Linux](https://github.com/The-Deichlers/Northrend-Launcher-Linux).

[Northrend Logs](https://github.com/The-Deichlers/northrend-logs) connects combat
reports to the portal. The [addon catalog](https://github.com/The-Deichlers/northrend-addon-catalog)
defines managed packages, including [Grid2](https://github.com/The-Deichlers/northrend-grid2),
[pfQuest](https://github.com/The-Deichlers/northrend-pfquest),
[MinimapGrabber](https://github.com/The-Deichlers/northrend-minimapgrabber), and
[RatingBuster](https://github.com/The-Deichlers/northrend-ratingbuster).
Companion addon work also includes [Raid Commander](https://github.com/gregdeichler/acore-raid-commander)
and [GM Tools](https://github.com/gregdeichler/acore-gm-tools).

The [experimental Northrend Client](https://github.com/The-Deichlers/Northrend-Client)
is an unofficial Whoa remix for exploring client-side features and refinements.

## Home Infrastructure

### [The Connected Home](https://github.com/The-Deichlers/home-infrastructure)

The operating manual for our connected home: network architecture, services,
media systems, automation, monitoring, backups, and recovery. Configuration and
documentation live together, so the systems we run and the records we keep agree.

| Find your way | Start here |
|---|---|
| **Understand the big picture** | [Connected systems](https://github.com/The-Deichlers/home-infrastructure/blob/main/docs/connected-systems.md) - what connects to what, and why |
| **Find a service** | [Service catalog](https://github.com/The-Deichlers/home-infrastructure/blob/main/inventory/service-catalog.md) - ownership, placement, and dependencies |
| **See what comes next** | [Roadmap](https://github.com/The-Deichlers/home-infrastructure/blob/main/ROADMAP.md) - priorities and acceptance gates |
| **Operate and recover** | [Documentation hub](https://github.com/The-Deichlers/home-infrastructure/blob/main/docs/README.md) - canonical runbooks and recovery procedures |

Our home systems also provide the local services and build runners that support
Northrend development. The infrastructure remains a first-class project in its
own right: useful household services, dependable automation, and recoverable data.

> **Repository access:** Most platform and infrastructure repositories are private
> and require authorized GitHub access. This public overview does not expose
> operational details, credentials, or private configuration.

## How we build

**Document the connections.** Give every system a purpose, an owner, and a
clear place in the bigger picture.

**Prove the change.** Keep implementation, live verification, and recovery
acceptance distinct. A running process is a beginning, not the finish line.

**Protect what matters.** Keep secrets out of source control, preserve rollback
paths, and make automation respect explicit approval boundaries.

**Keep it personal.** Build useful things for the people who actually use them.

---

<p align="center">
  <sub>Family-built · Version-controlled · Designed to keep working</sub>
</p>
