# Introduction to Talos Linux

A presentation introducing Talos Linux - the Kubernetes Operating System.

## About This Presentation

This slide deck provides a comprehensive introduction to Talos Linux for audiences who want to understand what Talos is, why it exists, and how it works.

### Topics Covered

- What is Talos Linux and who develops it (Sidero Labs)
- Core design principles: Secure, Immutable, Minimal
- Key features and architecture overview
- Security model (mTLS, no SSH, signed kernels)
- Immutability concepts and benefits
- Managing clusters with `talosctl`
- KubeSpan - WireGuard mesh networking
- Platform support (cloud, bare metal, Raspberry Pi)
- Use cases (production, edge, home labs, HPC)
- Getting started guide

### Slide Count

**18 slides** with presenter notes for each slide.

## Getting Started

### Install Dependencies

```bash
pnpm install
```

### Development Mode

```bash
pnpm dev
```

Opens the presentation at `http://localhost:3030`

### Presenter Mode

Press **P** during the presentation to view:
- Current and next slide
- Speaker notes
- Timer

### Export to PDF

```bash
pnpm export
```

### Build for Production

```bash
pnpm build
```

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Space` / `Right` | Next slide/animation |
| `Left` | Previous slide |
| `P` | Presenter mode |
| `O` | Slides overview |
| `F` | Fullscreen |

## Resources

- [Talos Linux](https://talos.dev)
- [GitHub - siderolabs/talos](https://github.com/siderolabs/talos)
- [Sidero Labs](https://siderolabs.com)
- [Slidev Documentation](https://sli.dev)

## Version Information

This presentation references:
- Talos Linux v1.11.x
- Kubernetes v1.32.x

> Check [Talos releases](https://github.com/siderolabs/talos/releases) for the latest versions before presenting.
