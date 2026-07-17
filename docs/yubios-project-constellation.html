<div id="yubios-project-constellation">
  <style>
    #yubios-project-constellation {
      display: grid;
      gap: 16px;
      color: var(--foreground);
    }

    #yubios-project-constellation .snapshot-grid {
      grid-template-columns: repeat(4, minmax(0, 1fr));
    }

    #yubios-project-constellation .metric-heading {
      display: flex;
      align-items: center;
      gap: 8px;
      color: var(--muted-foreground);
    }

    #yubios-project-constellation .metric-context {
      color: var(--muted-foreground);
    }

    #yubios-project-constellation .control-strip {
      justify-content: space-between;
      align-items: end;
    }

    #yubios-project-constellation .view-buttons {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
    }

    #yubios-project-constellation .focus-field {
      min-width: min(100%, 250px);
    }

    #yubios-project-constellation .constellation-stage {
      position: relative;
      overflow: hidden;
      border: 1px solid var(--border);
      border-radius: 18px;
      background:
        radial-gradient(circle at 50% 44%, color-mix(in srgb, var(--viz-series-1) 12%, transparent) 0, transparent 35%),
        radial-gradient(circle, color-mix(in srgb, var(--border) 55%, transparent) 1px, transparent 1.5px);
      background-size: auto, 18px 18px;
    }

    #yubios-project-constellation .constellation-svg {
      display: block;
      width: 100%;
      height: auto;
      overflow: visible;
    }

    #yubios-project-constellation .constellation-svg .edge {
      fill: none;
      stroke: var(--border);
      stroke-width: 2;
      transition: d 360ms cubic-bezier(.2, .8, .2, 1), stroke 160ms ease, stroke-width 160ms ease;
    }

    #yubios-project-constellation .constellation-svg .edge.is-connected {
      stroke: var(--primary);
      stroke-width: 3;
    }

    #yubios-project-constellation .constellation-svg .node-mark {
      cursor: pointer;
      transition: transform 360ms cubic-bezier(.2, .8, .2, 1);
    }

    #yubios-project-constellation .constellation-svg .node-surface {
      fill: color-mix(in srgb, var(--card) 86%, transparent);
      stroke: color-mix(in srgb, var(--node-color) 66%, var(--border));
      stroke-width: 2;
      transition: stroke 160ms ease, stroke-width 160ms ease, filter 160ms ease;
    }

    #yubios-project-constellation .constellation-svg .node-mark:hover .node-surface,
    #yubios-project-constellation .constellation-svg .node-mark.is-selected .node-surface {
      stroke: var(--primary);
      stroke-width: 4;
      filter: drop-shadow(0 0 9px color-mix(in srgb, var(--primary) 45%, transparent));
    }

    #yubios-project-constellation .constellation-svg .node-cap {
      fill: var(--node-color);
    }

    #yubios-project-constellation .constellation-svg .node-halo {
      fill: none;
      stroke: color-mix(in srgb, var(--node-color) 48%, transparent);
      stroke-width: 2;
    }

    #yubios-project-constellation .constellation-svg .node-label {
      fill: var(--foreground);
      font-weight: 500;
      pointer-events: none;
    }

    #yubios-project-constellation .constellation-svg .node-meta {
      fill: var(--muted-foreground);
      pointer-events: none;
    }

    #yubios-project-constellation .series-1 { --node-color: var(--viz-series-1); }
    #yubios-project-constellation .series-2 { --node-color: var(--viz-series-2); }
    #yubios-project-constellation .series-3 { --node-color: var(--viz-series-3); }
    #yubios-project-constellation .series-4 { --node-color: var(--viz-series-4); }
    #yubios-project-constellation .series-5 { --node-color: var(--viz-series-5); }
    #yubios-project-constellation .series-6 { --node-color: var(--viz-series-6); }

    #yubios-project-constellation .legend-swatch {
      width: 12px;
      height: 12px;
      border-radius: 50%;
      background: var(--node-color);
      flex: 0 0 auto;
    }

    #yubios-project-constellation .selection-card {
      display: grid;
      grid-template-columns: minmax(120px, .7fr) minmax(220px, 2fr) auto;
      gap: 12px;
      align-items: center;
    }

    #yubios-project-constellation .selection-identity {
      display: flex;
      align-items: center;
      gap: 8px;
      min-width: 0;
    }

    #yubios-project-constellation .selection-identity strong,
    #yubios-project-constellation .selection-detail {
      overflow-wrap: anywhere;
    }

    #yubios-project-constellation .snapshot-line {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 12px;
      color: var(--muted-foreground);
    }

    @media (max-width: 736px) {
      #yubios-project-constellation .snapshot-grid {
        grid-template-columns: repeat(2, minmax(0, 1fr));
      }

      #yubios-project-constellation .selection-card {
        grid-template-columns: 1fr;
      }
    }

    @media (max-width: 520px) {
      #yubios-project-constellation .snapshot-grid {
        grid-template-columns: 1fr;
      }

      #yubios-project-constellation .control-strip {
        align-items: stretch;
      }

      #yubios-project-constellation .focus-field {
        width: 100%;
      }

      #yubios-project-constellation .snapshot-line {
        align-items: flex-start;
        flex-direction: column;
      }
    }

    @media (prefers-reduced-motion: reduce) {
      #yubios-project-constellation .constellation-svg .edge,
      #yubios-project-constellation .constellation-svg .node-mark,
      #yubios-project-constellation .constellation-svg .node-surface {
        transition: none;
      }
    }
  </style>

  <div class="viz-grid snapshot-grid" aria-label="Project snapshot">
    <div class="card viz-stat">
      <div class="metric-heading"><i data-lucide="git-commit-horizontal" aria-hidden="true"></i><span>Repository history</span></div>
      <div class="viz-stat-value">661</div>
      <div class="text-small metric-context">commits since May 9, 2026</div>
    </div>
    <div class="card viz-stat">
      <div class="metric-heading"><i data-lucide="workflow" aria-hidden="true"></i><span>Delivery surface</span></div>
      <div class="viz-stat-value">19</div>
      <div class="text-small metric-context">workflow files in the CI map</div>
    </div>
    <div class="card viz-stat">
      <div class="metric-heading"><i data-lucide="list-checks" aria-hidden="true"></i><span>Active checklist</span></div>
      <div class="viz-stat-value">34 / 54</div>
      <div class="text-small metric-context">complete · 20 remain open</div>
    </div>
    <div class="card viz-stat">
      <div class="metric-heading"><i data-lucide="shield-alert" aria-hidden="true"></i><span>Current constraints</span></div>
      <div class="viz-stat-value">7</div>
      <div class="text-small metric-context">active blockers on the register</div>
    </div>
  </div>

  <div class="viz-controls control-strip">
    <div>
      <div class="form-label">Explore</div>
      <div class="view-buttons" role="group" aria-label="Project view">
        <button type="button" class="btn btn-primary" data-project-view="architecture" aria-pressed="true">Trust system</button>
        <button type="button" class="btn" data-project-view="delivery" aria-pressed="false">Build &amp; delivery</button>
        <button type="button" class="btn" data-project-view="roadmap" aria-pressed="false">Execution</button>
        <button type="button" class="btn" data-project-view="ecosystem" aria-pressed="false">Repo ecosystem</button>
      </div>
    </div>
    <label class="form-label focus-field" for="yubios-focus-node">
      Focus
      <select id="yubios-focus-node" class="form-select"></select>
    </label>
  </div>

  <div class="constellation-stage">
    <svg id="yubios-constellation-svg" class="constellation-svg" viewBox="0 0 760 440" width="760" height="440" role="img" aria-labelledby="yubios-map-title yubios-map-desc">
      <title id="yubios-map-title">Interactive yubiOS project map</title>
      <desc id="yubios-map-desc">The trust system view connects the owner-held YubiKey to signing, identity, unlock, integrity, and measurement controls.</desc>
      <defs>
        <marker id="yubios-arrow" markerWidth="7" markerHeight="7" refX="6" refY="3.5" orient="auto" markerUnits="strokeWidth">
          <path d="M0,0 L7,3.5 L0,7 Z" fill="var(--border)"></path>
        </marker>
      </defs>
      <g id="yubios-edge-layer"></g>
      <g id="yubios-node-layer"></g>
    </svg>
  </div>

  <div id="yubios-legend" class="viz-legend text-small" aria-label="Current view legend"></div>

  <div class="card selection-card" aria-live="polite">
    <div class="selection-identity">
      <span id="yubios-selection-badge" class="viz-badge">Owner authority</span>
      <strong id="yubios-selection-name">YubiKey 5</strong>
    </div>
    <div id="yubios-selection-detail" class="selection-detail">The owner-held root gates PIV signing, disk and home unlock, SSH, PAM, and application 2FA; platform measurement remains a separate signal.</div>
    <a id="yubios-selection-link" class="btn btn-ghost" href="https://github.com/yubi-OS/yubiOS/blob/main/ARCHITECTURE.md" target="_blank" rel="noreferrer">Open source</a>
  </div>

  <div class="snapshot-line text-small">
    <span>Groundwork / pre-launch · ARM64 primary · x86-64 supported</span>
    <span><code>main@8a2768d</code> · snapshot 2026-07-17</span>
  </div>

  <script>
    (() => {
      const root = document.getElementById("yubios-project-constellation");
      if (!root) return;

      const svg = document.getElementById("yubios-constellation-svg");
      const nodeLayer = document.getElementById("yubios-node-layer");
      const edgeLayer = document.getElementById("yubios-edge-layer");
      const focusSelect = document.getElementById("yubios-focus-node");
      const legend = document.getElementById("yubios-legend");
      const selectionBadge = document.getElementById("yubios-selection-badge");
      const selectionName = document.getElementById("yubios-selection-name");
      const selectionDetail = document.getElementById("yubios-selection-detail");
      const selectionLink = document.getElementById("yubios-selection-link");
      const description = document.getElementById("yubios-map-desc");
      const ns = "http://www.w3.org/2000/svg";
      const compactQuery = window.matchMedia("(max-width: 520px)");
      const reduceMotionQuery = window.matchMedia("(prefers-reduced-motion: reduce)");
      const sourceBase = "https://github.com/yubi-OS/yubiOS/blob/main/";

      const views = {
        architecture: {
          description: "The trust system view connects the owner-held YubiKey to signing, identity, unlock, integrity, and measurement controls.",
          initial: "owner",
          legend: [
            ["series-1", "Owner authority"],
            ["series-2", "Identity & unlock"],
            ["series-3", "Verified system"],
            ["series-4", "Platform evidence"]
          ],
          nodes: [
            { id: "owner", label: "YubiKey 5", meta: "owner root", x: 90, y: 220, series: "series-1", pulse: true, badge: "Owner authority", detail: "The owner-held root gates PIV signing, disk and home unlock, SSH, PAM, and application 2FA; platform measurement remains a separate signal.", url: sourceBase + "ARCHITECTURE.md" },
            { id: "piv", label: "PIV slot 9c", meta: "CCID / PKCS#11", x: 250, y: 65, series: "series-2", badge: "Signing", detail: "PIV slot 9c signs Secure Boot and UKI artifacts with systemd-sbsign; this path uses CCID, not FIDO2 hidraw.", url: sourceBase + "ADR.md#adr-002-secure-boot-signing-via-piv-ccid-not-fido2-hidraw" },
            { id: "fido", label: "FIDO2 secret", meta: "PIN + touch", x: 250, y: 170, series: "series-2", badge: "Unlock", detail: "FIDO2 hmac-secret protects root, swap, and per-user homes while an offline recovery key preserves recoverability.", url: sourceBase + "SPEC.md#4-interface-requirements" },
            { id: "ssh", label: "SSH resident key", meta: "ed25519-sk", x: 250, y: 275, series: "series-2", badge: "Identity", detail: "Resident ed25519-sk credentials provide hardware-backed SSH identity; administrative keys should require verification and PIN.", url: sourceBase + "ARCHITECTURE.md#trust-boundaries" },
            { id: "pam", label: "PAM U2F", meta: "login + sudo", x: 250, y: 380, series: "series-2", badge: "Presence", detail: "pam-u2f 1.3.1+ is composed as required, keeping physical presence mandatory for login and privileged actions.", url: sourceBase + "SPEC.md#4-interface-requirements" },
            { id: "uki", label: "Signed UKI", meta: "kernel + initrd", x: 430, y: 65, series: "series-3", badge: "Boot integrity", detail: "The signed UKI binds kernel, initrd, command line, and the dm-verity root needed to authenticate the immutable system.", url: sourceBase + "THREAT_MODEL.md#security-invariants" },
            { id: "luks", label: "LUKS2 root", meta: "root + swap", x: 430, y: 170, series: "series-3", badge: "Encrypted state", detail: "Writable root state and swap are encrypted with LUKS2 and unlocked through FIDO2 plus explicitly managed recovery material.", url: sourceBase + "ARCHITECTURE.md#boot-flow" },
            { id: "homed", label: "Encrypted homes", meta: "systemd-homed", x: 430, y: 255, series: "series-3", badge: "User isolation", detail: "systemd-homed gives each user a FIDO2-gated LUKS2 home, separate from the immutable operating-system image.", url: sourceBase + "ARCHITECTURE.md#trust-boundaries" },
            { id: "verity", label: "Verified /usr", meta: "dm-verity", x: 610, y: 65, series: "series-3", badge: "Runtime integrity", detail: "Every read from immutable /usr is intended to be hash-verified through composefs, erofs, and dm-verity.", url: sourceBase + "SPEC.md#6-runtime-filesystem-requirements" },
            { id: "updates", label: "A/B updates", meta: "boot counter", x: 680, y: 165, series: "series-3", badge: "Recovery", detail: "Atomic A/B /usr updates retain a known-good slot and use a three-attempt boot counter before health is accepted.", url: sourceBase + "ARCHITECTURE.md#build-and-distribution" },
            { id: "ftpm", label: "TPM / fTPM", meta: "PCR evidence", x: 610, y: 275, series: "series-4", badge: "Measurement", detail: "TPM or fTPM evidence answers what platform booted; it complements YubiKey possession and must not become the sole unlock gate.", url: sourceBase + "SPEC.md#3-trust-model" }
          ],
          edges: [["owner", "piv"], ["owner", "fido"], ["owner", "ssh"], ["owner", "pam"], ["piv", "uki"], ["fido", "luks"], ["fido", "homed"], ["uki", "verity"], ["uki", "ftpm"], ["verity", "updates"]]
        },
        delivery: {
          description: "The build and delivery view follows approved inputs through policy, builders, the orchestrated workflow chain, verification, and separated release channels.",
          initial: "ci",
          legend: [
            ["series-1", "Pinned control"],
            ["series-2", "Build lane"],
            ["series-3", "CI & evidence"],
            ["series-5", "Release channel"]
          ],
          nodes: [
            { id: "pins", label: "PINNED.md", meta: "SHAs + digests", x: 80, y: 215, series: "series-1", badge: "Source of truth", detail: "Approved GitHub Action SHAs and container digests are centralized here; mutable references are rejected.", url: sourceBase + "PINNED.md" },
            { id: "policy", label: "Rego policy", meta: "strict gate", x: 225, y: 95, series: "series-1", badge: "Supply chain", detail: "yubiOS.rego gates build inputs before layers execute and enforces canonical, digest-pinned sources.", url: sourceBase + "yubiOS.rego" },
            { id: "source", label: "OS overlay", meta: "usr + configs", x: 225, y: 335, series: "series-2", badge: "Source", detail: "Runtime scripts, systemd units, PAM policy, repart definitions, and test profiles make up the OS overlay.", url: "https://github.com/yubi-OS/yubiOS/tree/main/usr" },
            { id: "bootc", label: "bootc / OCI", meta: "day-2 stream", x: 380, y: 95, series: "series-2", badge: "Builder", detail: "The bootc path produces the multi-architecture operating-system update stream and VM test source.", url: sourceBase + "ARCHITECTURE.md#build-and-distribution" },
            { id: "mkosi", label: "mkosi", meta: "UKI + installer", x: 380, y: 215, series: "series-2", badge: "Builder", detail: "The mkosi path builds signed UKIs and installer images, using SoftHSM in CI to validate the PKCS#11 signing flow.", url: sourceBase + "mkosi.conf" },
            { id: "firmware", label: "RK firmware", meta: "Path A stack", x: 380, y: 335, series: "series-2", badge: "Builder", detail: "The orchestrated RK lane composes TF-A, OP-TEE, fTPM, StandaloneMM, U-Boot, and board-specific firmware payloads.", url: sourceBase + ".github/workflows/ci_firmware-rk.yml" },
            { id: "ci", label: "CI coordinator", meta: "19 workflows", x: 525, y: 215, series: "series-3", pulse: true, badge: "State machine", detail: "ci.yml coordinates digest refresh, optional fork checks, RK firmware, production, dev, VM, installer, and PQ TLS lanes through callbacks.", url: sourceBase + "CI_MAP.md#top-level-state-machine" },
            { id: "attest", label: "Evidence", meta: "SBOM + SLSA", x: 525, y: 385, series: "series-3", badge: "Attestation", detail: "Published artifacts are expected to carry provenance and SBOM evidence; pinning records identity but does not prove trustworthiness.", url: sourceBase + "THREAT_MODEL.md#principal-attacker-stories" },
            { id: "prod", label: "Production", meta: "latest + SHA", x: 685, y: 65, series: "series-5", badge: "Release channel", detail: "Production bootc images publish board-neutral latest and immutable commit tags, with dev authenticators excluded.", url: sourceBase + "CI_MAP.md#production-dev-vm-installer-and-pq-lanes" },
            { id: "dev", label: "Dev / test", meta: "swu2f isolated", x: 685, y: 155, series: "series-5", badge: "Test channel", detail: "dev and dev-<sha> images may carry the software FIDO2 authenticator only under explicit TEST-only separation.", url: sourceBase + "SPEC.md#7-update-requirements" },
            { id: "vm", label: "VM e2e", meta: "bcvk", x: 685, y: 245, series: "series-5", badge: "Validation", detail: "The bcvk VM lane exercises boot, LUKS/FIDO2, enrollment, SSH, and platform paths while keeping software evidence distinct from hardware proof.", url: sourceBase + ".github/workflows/ci_test-vm.yml" },
            { id: "installer", label: "Installer", meta: "raw.zst + OCI", x: 685, y: 335, series: "series-5", badge: "Release channel", detail: "The installer lane validates a signed UKI and can publish installer and installer-<sha> artifacts separately from the OS stream.", url: sourceBase + ".github/workflows/ci_mkosi-installer.yml" }
          ],
          edges: [["pins", "policy"], ["pins", "firmware"], ["policy", "bootc"], ["source", "bootc"], ["source", "mkosi"], ["source", "firmware"], ["bootc", "ci"], ["mkosi", "ci"], ["firmware", "ci"], ["ci", "prod"], ["ci", "dev"], ["ci", "vm"], ["ci", "installer"], ["ci", "attest"]]
        },
        roadmap: {
          description: "The execution view shows exact completion counts from the active TODO checklist and the open evidence concentrated behind seven registered blockers.",
          initial: "execution",
          legend: [
            ["series-3", "100% complete"],
            ["series-2", "75–99% complete"],
            ["series-4", "50% complete"],
            ["series-6", "Below 50% complete"]
          ],
          nodes: [
            { id: "execution", label: "Execution", meta: "34 / 54 done", x: 380, y: 220, series: "series-1", pulse: true, badge: "Active plan", detail: "The active TODO has 34 completed and 20 open items. The blocker register names seven current constraints; no pull requests are open and nine issues remain open.", url: sourceBase + "TODO.md" },
            { id: "docs", label: "Documentation", meta: "9 / 9", x: 120, y: 70, series: "series-3", badge: "Checklist · 100%", detail: "All nine current documentation tasks are checked off, including dated research notes, install guidance, and the systemd v262 audit.", url: sourceBase + "TODO.md#current-documentation-tasks" },
            { id: "research", label: "Roadmap research", meta: "14 / 17", x: 380, y: 65, series: "series-2", badge: "Checklist · 82%", detail: "Open proof work is concentrated in Frost hardware behavior and the OpenWrt deception-LAN VM plus packet evidence.", url: sourceBase + "TODO.md#current-roadmap-research-tasks" },
            { id: "security", label: "Security", meta: "4 / 5", x: 640, y: 70, series: "series-2", badge: "Checklist · 80%", detail: "Static hardening and recovery discipline are documented; refreshed real-hardware YubiKey evidence remains open.", url: sourceBase + "TODO.md#current-security-tasks" },
            { id: "supply", label: "Supply chain", meta: "3 / 6", x: 120, y: 365, series: "series-4", badge: "Checklist · 50%", detail: "Open work covers pin rotation, package-floor checks, and preserving provenance and SBOM expectations across published artifacts.", url: sourceBase + "TODO.md#current-supply-chain-tasks" },
            { id: "arm64", label: "ARM64 Path A", meta: "2 / 6", x: 380, y: 375, series: "series-6", badge: "Checklist · 33%", detail: "ROCK 5B is selected, but sacrificial fuse rehearsal, RPMB-backed secure-world proof, exact configs, and cross-architecture UKI evidence remain.", url: sourceBase + "BLOCKERS.md#active-blockers" },
            { id: "ciwork", label: "CI", meta: "2 / 11", x: 640, y: 365, series: "series-6", badge: "Checklist · 18%", detail: "The heaviest open lane: validate bootloader-update and SSH fixes, keep QEMU and PQ gates honest, preserve dev/prod isolation, and prove the install path.", url: sourceBase + "TODO.md#current-ci-tasks" }
          ],
          edges: [["execution", "docs"], ["execution", "research"], ["execution", "security"], ["execution", "supply"], ["execution", "arm64"], ["execution", "ciwork"]]
        },
        ecosystem: {
          description: "The repository ecosystem view places the main OS beside the declared build, virtualization, firmware, and reference repositories used by the project.",
          initial: "yubios",
          legend: [
            ["series-1", "Core project"],
            ["series-2", "Build & virtualization"],
            ["series-4", "Secure firmware stack"],
            ["series-5", "Reference implementation"]
          ],
          nodes: [
            { id: "yubios", label: "yubiOS", meta: "main project", x: 355, y: 220, series: "series-1", pulse: true, badge: "Core", detail: "The organization exposes 17 repositories. AGENTS.md declares 13 project repositories, while period-named repositories are explicitly hands-off.", url: "https://github.com/yubi-OS/yubiOS" },
            { id: "bootcrepo", label: "bootc", meta: "OCI delivery", x: 90, y: 65, series: "series-2", badge: "Active fork", detail: "Bootable OCI image delivery and day-2 operating-system updates.", url: "https://github.com/yubi-OS/bootc" },
            { id: "bcvkrepo", label: "bcvk", meta: "VM / disk kit", x: 90, y: 170, series: "series-2", badge: "Active fork", detail: "Virtualization and native-to-disk test kit used by yubiOS CI, including FIDO2 and TPM-oriented VM work.", url: "https://github.com/yubi-OS/bcvk" },
            { id: "mkosirepo", label: "mkosi", meta: "image builder", x: 90, y: 275, series: "series-2", badge: "Active fork", detail: "Image and UKI builder supporting installer, profile, and signing validation.", url: "https://github.com/yubi-OS/mkosi" },
            { id: "particle", label: "particleos", meta: "reference", x: 90, y: 380, series: "series-5", badge: "Reference only", detail: "Reference implementation and architectural inspiration for immutable /usr, UKIs, composefs, and the systemd image model.", url: "https://github.com/yubi-OS/particleos" },
            { id: "tfa", label: "TF-A", meta: "BL31 / TBB", x: 520, y: 45, series: "series-4", badge: "ARM64 stack", detail: "Trusted Firmware-A supplies the EL3 secure monitor and Trusted Board Boot foundation for ARM64 Path A.", url: "https://github.com/yubi-OS/arm-trusted-firmware" },
            { id: "optee", label: "OP-TEE", meta: "secure world", x: 660, y: 105, series: "series-4", badge: "ARM64 stack", detail: "Secure-world OS hosting trusted applications such as fTPM and the StandaloneMM variable service.", url: "https://github.com/yubi-OS/optee_os" },
            { id: "opteeftpm", label: "OP-TEE fTPM", meta: "trusted app", x: 690, y: 200, series: "series-4", badge: "ARM64 stack", detail: "fTPM trusted application integrated with the TPM 2.0 reference implementation for measured-boot evidence.", url: "https://github.com/yubi-OS/optee_ftpm" },
            { id: "uboot", label: "U-Boot", meta: "BL33 + UEFI", x: 675, y: 300, series: "series-4", badge: "ARM64 stack", detail: "BL33 and UEFI provider responsible for Secure Boot variables, TCG2 measurement, and loading systemd-boot plus the signed UKI.", url: "https://github.com/yubi-OS/u-boot" },
            { id: "mstpm", label: "ms-tpm-20-ref", meta: "TPM engine", x: 570, y: 390, series: "series-4", badge: "ARM64 stack", detail: "TPM 2.0 reference engine used by the secure-world fTPM integration.", url: "https://github.com/yubi-OS/ms-tpm-20-ref" },
            { id: "edk2", label: "EDK2", meta: "StandaloneMM", x: 415, y: 390, series: "series-4", badge: "ARM64 support", detail: "Source for the RPMB-oriented StandaloneMM UEFI variable service used in the firmware integration path.", url: "https://github.com/yubi-OS/edk2" },
            { id: "edk2rk", label: "EDK2 RK3588", meta: "board reference", x: 385, y: 65, series: "series-5", badge: "Reference only", detail: "RK3588 firmware reference used for board research, not the normative yubiOS implementation path.", url: "https://github.com/yubi-OS/edk2-rk3588" }
          ],
          edges: [["bootcrepo", "yubios"], ["bcvkrepo", "yubios"], ["mkosirepo", "yubios"], ["particle", "yubios"], ["edk2rk", "yubios"], ["tfa", "optee"], ["optee", "opteeftpm"], ["mstpm", "opteeftpm"], ["edk2", "optee"], ["tfa", "uboot"], ["opteeftpm", "yubios"], ["uboot", "yubios"]]
        }
      };

      let currentView = "architecture";
      let selectedId = views[currentView].initial;
      let firstRender = true;

      const createSvg = (name, attributes = {}) => {
        const element = document.createElementNS(ns, name);
        Object.entries(attributes).forEach(([key, value]) => element.setAttribute(key, String(value)));
        return element;
      };

      const splitLabel = label => {
        if (label.length <= 16) return [label];
        const words = label.split(" ");
        const midpoint = Math.ceil(words.length / 2);
        return [words.slice(0, midpoint).join(" "), words.slice(midpoint).join(" ")];
      };

      const getLayout = view => {
        if (!compactQuery.matches) {
          return {
            width: 760,
            height: 440,
            centerX: 380,
            centerY: 220,
            nodes: new Map(view.nodes.map(node => [node.id, { ...node, width: 124, height: 56 }]))
          };
        }

        const columns = 2;
        const xPositions = [86, 254];
        const rowGap = 84;
        const top = 62;
        const rows = Math.ceil(view.nodes.length / columns);
        const height = Math.max(300, top + (rows - 1) * rowGap + 68);
        return {
          width: 340,
          height,
          centerX: 170,
          centerY: height / 2,
          nodes: new Map(view.nodes.map((node, index) => [node.id, {
            ...node,
            x: xPositions[index % columns],
            y: top + Math.floor(index / columns) * rowGap,
            width: 150,
            height: 60
          }]))
        };
      };

      const makeEdgePath = (from, to) => {
        const dx = to.x - from.x;
        const dy = to.y - from.y;
        const distance = Math.max(1, Math.hypot(dx, dy));
        const fromPad = Math.min(from.width, from.height) * .43;
        const toPad = Math.min(to.width, to.height) * .54;
        const x1 = from.x + dx / distance * fromPad;
        const y1 = from.y + dy / distance * fromPad;
        const x2 = to.x - dx / distance * toPad;
        const y2 = to.y - dy / distance * toPad;
        return `M ${x1} ${y1} L ${x2} ${y2}`;
      };

      const renderLegend = view => {
        legend.replaceChildren();
        view.legend.forEach(([series, label]) => {
          const item = document.createElement("span");
          item.className = series;
          const swatch = document.createElement("span");
          swatch.className = "legend-swatch";
          swatch.setAttribute("aria-hidden", "true");
          const text = document.createElement("span");
          text.textContent = label;
          item.append(swatch, text);
          legend.append(item);
        });
      };

      const setSelected = id => {
        const view = views[currentView];
        const node = view.nodes.find(item => item.id === id) || view.nodes[0];
        selectedId = node.id;
        focusSelect.value = node.id;
        selectionBadge.textContent = node.badge;
        selectionName.textContent = node.label;
        selectionDetail.textContent = node.detail;
        selectionLink.href = node.url;
        nodeLayer.querySelectorAll(".node-mark").forEach(mark => {
          mark.classList.toggle("is-selected", mark.dataset.id === node.id);
        });
        edgeLayer.querySelectorAll(".edge").forEach(edge => {
          edge.classList.toggle("is-connected", edge.dataset.from === node.id || edge.dataset.to === node.id);
        });
      };

      const renderView = (viewName, immediate = false) => {
        currentView = viewName;
        const view = views[viewName];
        const layout = getLayout(view);
        const shouldAnimate = !firstRender && !immediate && !reduceMotionQuery.matches;
        svg.setAttribute("viewBox", `0 0 ${layout.width} ${layout.height}`);
        svg.setAttribute("width", String(layout.width));
        svg.setAttribute("height", String(layout.height));
        description.textContent = view.description;
        nodeLayer.replaceChildren();
        edgeLayer.replaceChildren();

        const centerNode = { x: layout.centerX, y: layout.centerY, width: 1, height: 1 };
        const edgeRecords = [];
        view.edges.forEach(([fromId, toId]) => {
          const from = layout.nodes.get(fromId);
          const to = layout.nodes.get(toId);
          if (!from || !to) return;
          const path = createSvg("path", {
            class: "edge",
            d: shouldAnimate ? makeEdgePath(centerNode, centerNode) : makeEdgePath(from, to),
            "marker-end": "url(#yubios-arrow)",
            "data-from": fromId,
            "data-to": toId
          });
          edgeLayer.append(path);
          edgeRecords.push({ path, from, to });
        });

        view.nodes.forEach(nodeData => {
          const node = layout.nodes.get(nodeData.id);
          const group = createSvg("g", {
            class: `node-mark ${node.series}`,
            transform: shouldAnimate ? `translate(${layout.centerX} ${layout.centerY})` : `translate(${node.x} ${node.y})`,
            "data-id": node.id,
            "aria-label": `${node.label}: ${node.meta}`
          });
          const title = createSvg("title");
          title.textContent = `${node.label} — ${node.meta}`;
          group.append(title);

          if (node.pulse) {
            group.append(createSvg("ellipse", {
              class: "node-halo",
              cx: 0,
              cy: 0,
              rx: node.width / 2 + 9,
              ry: node.height / 2 + 9
            }));
          }

          group.append(createSvg("rect", {
            class: "node-surface",
            x: -node.width / 2,
            y: -node.height / 2,
            width: node.width,
            height: node.height,
            rx: 15,
            ry: 15
          }));
          group.append(createSvg("rect", {
            class: "node-cap",
            x: -node.width / 2,
            y: -node.height / 2,
            width: 7,
            height: node.height,
            rx: 4,
            ry: 4
          }));

          const lines = splitLabel(node.label);
          const label = createSvg("text", {
            class: "node-label",
            x: 4,
            y: lines.length === 1 ? -3 : -10,
            "text-anchor": "middle"
          });
          lines.forEach((line, index) => {
            const tspan = createSvg("tspan", { x: 4, dy: index === 0 ? 0 : 16 });
            tspan.textContent = line;
            label.append(tspan);
          });
          group.append(label);

          const meta = createSvg("text", {
            class: "node-meta text-small",
            x: 4,
            y: lines.length === 1 ? 17 : 19,
            "text-anchor": "middle"
          });
          meta.textContent = node.meta;
          group.append(meta);
          group.addEventListener("click", () => setSelected(node.id));
          nodeLayer.append(group);

          if (shouldAnimate) {
            requestAnimationFrame(() => group.setAttribute("transform", `translate(${node.x} ${node.y})`));
          }
        });

        if (shouldAnimate) {
          requestAnimationFrame(() => {
            edgeRecords.forEach(record => record.path.setAttribute("d", makeEdgePath(record.from, record.to)));
          });
        }

        focusSelect.replaceChildren();
        view.nodes.forEach(node => {
          const option = document.createElement("option");
          option.value = node.id;
          option.textContent = `${node.label} — ${node.meta}`;
          focusSelect.append(option);
        });
        renderLegend(view);
        setSelected(view.initial);

        root.querySelectorAll("[data-project-view]").forEach(button => {
          const active = button.dataset.projectView === viewName;
          button.classList.toggle("btn-primary", active);
          button.setAttribute("aria-pressed", active ? "true" : "false");
        });
        firstRender = false;
      };

      root.querySelectorAll("[data-project-view]").forEach(button => {
        button.addEventListener("click", () => renderView(button.dataset.projectView));
      });
      focusSelect.addEventListener("change", event => setSelected(event.target.value));
      compactQuery.addEventListener("change", () => renderView(currentView, true));
      reduceMotionQuery.addEventListener("change", () => renderView(currentView, true));
      renderView(currentView, true);
    })();
  </script>
</div>
