<img src="https://raw.githubusercontent.com/Rogue-Machine-Podcast/.github/main/profile/banner.svg" alt="ROGUE MACHINE. The public case files behind the podcast." width="100%">

### Start here

**Rogue Machine** is a true-crime podcast by Brian Spector and Nicola McNamee. These three repositories hold the public record the show draws on: two criminal referrals they filed with U.S. authorities in 2026, and the evidence archive for the first one.

Read them in this order:

1. **[EEA / 01 — Victim Referral](https://github.com/Rogue-Machine-Podcast/EEA-Victim-Referral).** Start with the [executive summary](https://github.com/Rogue-Machine-Podcast/EEA-Victim-Referral/blob/main/01_EXECUTIVE_SUMMARY_V6_FINAL.md). It is Brian's account of how he says his company's trade secrets were taken, who he names, and what he asked the FBI to investigate.
2. **[EEA / 02 — Evidence](https://github.com/Rogue-Machine-Podcast/EEA-Evidence).** The exhibits that referral cites. Open the [evidence index](https://github.com/Rogue-Machine-Podcast/EEA-Evidence/blob/main/EVIDENCE_INDEX.md) to see each file, where it is cited and its SHA-256 hash.
3. **[HRSP / 01 — County Tyrone](https://github.com/Rogue-Machine-Podcast/hrsp-submission-genocide-county-tyrone).** A separate referral from Brian and Nicola. It alleges that Nicola's UK hospital records were fabricated and places them in a wider pattern it describes. The README gives the overview.

<table width="100%">
  <tr>
    <td width="33%" valign="top">
      <a href="https://github.com/Rogue-Machine-Podcast/EEA-Victim-Referral">
        <img src="https://raw.githubusercontent.com/Rogue-Machine-Podcast/.github/main/profile/card-eea-victim-referral.svg" alt="EEA 01, start here: Victim Referral. Our referral, as submitted. 18 U.S.C. § 1831, FBI / DOJ." width="100%">
      </a>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/Rogue-Machine-Podcast/EEA-Evidence">
        <img src="https://raw.githubusercontent.com/Rogue-Machine-Podcast/.github/main/profile/card-eea-evidence.svg" alt="EEA 02: Evidence. Exhibits cited by EEA 01, with a SHA-256 hash for every file." width="100%">
      </a>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/Rogue-Machine-Podcast/hrsp-submission-genocide-county-tyrone">
        <img src="https://raw.githubusercontent.com/Rogue-Machine-Podcast/.github/main/profile/card-hrsp-tyrone.svg" alt="HRSP 01: County Tyrone. Our referral, as submitted. 18 U.S.C. §§ 1091, 2340, DOJ HRSP." width="100%">
      </a>
    </td>
  </tr>
</table>

### How to read these files

The archives mix four kinds of material. Each one carries a different weight.

- **Allegation.** Our account and conclusions, as we submitted them. The referrals, narratives, profiles and convergence analyses are ours.
- **Source document.** A record made by someone else, such as court papers, medical records, emails or screenshots. Kept as received and listed with a hash.
- **Our annotation.** Notes we added about a source, such as the "What it proves" lines in the evidence index. They are our reading of the document, not part of it.
- **Official finding.** A decision by a court or agency. Only these carry official weight, so check any we cite against the court's or agency's own record.

A referral asks an agency to investigate. Sending one does not mean the agency has reviewed, accepted or confirmed what it says. A matching hash shows that a file hasn't changed since it was listed. It does not show that the file's contents are true.

### Index

- **[EEA&nbsp;/&nbsp;01 — Victim Referral](https://github.com/Rogue-Machine-Podcast/EEA-Victim-Referral).** Economic Espionage Act victim referral (18 U.S.C. § 1831) addressed to the FBI and DOJ, submitted through Congressman Cloud's office in February 2026.
- **[EEA&nbsp;/&nbsp;02 — Evidence](https://github.com/Rogue-Machine-Podcast/EEA-Evidence).** The exhibits cited by EEA&nbsp;/&nbsp;01, including material from the related UK civil case BL-2024-000648.
- **[HRSP&nbsp;/&nbsp;01 — County Tyrone](https://github.com/Rogue-Machine-Podcast/hrsp-submission-genocide-county-tyrone).** Referral to the DOJ Human Rights and Special Prosecutions Section alleging genocide and torture (18 U.S.C. §§ 1091, 2340), transmitted through Senator Ted Cruz's office on 5 March 2026.

**EEA** is the Economic Espionage Act. **HRSP** is the DOJ's Human Rights and Special Prosecutions Section. **BL-2024-000648** is the claim number of the related UK civil case.

To check a file, run `shasum -a 256 <file>` and compare the result with the archive's manifest: `SHA256SUMS.txt` (EEA / 01), `HASH_MANIFEST.md` (EEA / 02) or `SHA256_MANIFEST.txt` (HRSP / 01). All three archives are licensed CC BY-NC-ND 4.0.

### Also in this org

The other public repositories are forks of outside open-source projects that our production team uses, mostly agent tooling, local model inference and web crawling. They hold no case material. [Browse them separately](https://github.com/search?q=org%3ARogue-Machine-Podcast+topic%3Aproduction-tooling+fork%3Atrue&type=repositories).

---

**Listen:** [roguemachinepod.com](https://roguemachinepod.com) · **X:** [@RogueMachinePod](https://x.com/RogueMachinePod) · **Contact:** brian@roguemachinepod.com

<sub>ROGUE MACHINE // PUBLIC ACCESS</sub>
