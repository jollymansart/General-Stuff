# Review notes — AHEAD, Senior Technical Consultant (Azure Local & Hyper-V)

$150–190k OTE · Remote · Read before sending.

---

## 1. The one thing you may have read backwards

The JD's **"Use of AI"** section is AHEAD telling you *they* use AI to screen applicants. It
is not a request for candidates who use AI. Nothing in Required or Preferred Qualifications
mentions AI fluency.

So I cut the standalone **"How I Work With AI"** section. On a two-page resume for this role,
that space belongs to Azure Local and Hyper-V. Your AI-assisted scripting survives as a clause
under **Automation** in Technical Skills, which is where this employer would look for it — they
ask for "PowerShell, Python, Ansible, Terraform," not for AI tools.

Say the word and I'll restore the section. For a different posting — one that genuinely
screens for AI adoption — it's still the right move, and it's in the git history.

**The line that does matter** is this one:

> *"...identifying potential inconsistencies or verification signals in application materials
> based on available information."*

Your resume will be machine-compared against your LinkedIn. See §5.

---

## 2. Where you stand against the requirements

**You are much closer to this job than your title suggests.** Azure Local (formerly Azure Stack
HCI) is, mechanically, Storage Spaces Direct clusters on validated hardware, registered to Azure
via Arc, managed through Windows Admin Center. **You already run three of those four pieces in
production.**

### Direct hits — these are why you get the interview

| JD requirement | What you have |
|---|---|
| Migrate VMware → Hyper-V *(named twice)* | You led exactly this migration |
| Hyper-V failover clusters, HA workloads | In production now |
| Storage Spaces Direct | Built hyper-converged hosts on it |
| Windows Admin Center *(named explicitly)* | Standardized management on it |
| Windows Server, AD, DNS, Group Policy, PowerShell | 17 years, currently owned end to end |
| VMware vSphere / vCenter / vSAN *(preferred)* | All three |
| Server hardware, capacity planning, performance | Five storage platforms, 500+ servers |
| Technical documentation, runbooks, as-builts | A genuine strength — the JD asks for it in three separate bullets |
| Consulting / customer-facing delivery *(preferred)* | Smart Shared Services was client engagement work |
| DR, backup, replication, hybrid *(preferred)* | Site-to-site replication, DPM, Azure + OCI |

### The real gaps — be ready for these

1. **Azure Local / Azure Stack HCI by name.** This is *the* required qualification and the job
   title. You have the substrate but not the product. Don't claim it. **Do** be ready to say:
   *"I've built and run S2D hyper-converged clusters with failover clustering and manage them
   through Windows Admin Center — what I haven't done is the Arc registration and Network ATC
   layer on top, and that's the part I'd close first."* That answer is credible. Claiming Azure
   Local outright is not, and this is a firm that will test it.
2. **Azure Arc** — not on your record. Same handling.
3. **Network ATC** — Azure Local–specific. Same.
4. **Azure Migrate, Azure Monitor, Azure Policy, Defender for Cloud** — preferred, not required.
   If you've touched any, tell me and I'll add them.
5. **Terraform / Ansible / Python** — preferred. You have PowerShell, which is the one they name
   first. Fine as-is.
6. **Certifications — you have none listed, and the JD prefers them.** AHEAD explicitly sponsors
   certifications, which cuts both ways: they value them, and they'll train you. **AZ-800 and
   AZ-801** (Windows Server Hybrid Administrator) cover Azure Local, Arc, and hybrid AD directly.
   Even one *in progress* on the resume would close the most visible gap. Tell me if you start
   one and I'll add a line.
7. **Kubernetes / AKS on Arc** — preferred, likely a gap. Low priority.

### The honest overall read

You clear every Required qualification except the Azure Local one, and you clear most Preferred
ones. The gap is one product layer, not a category of experience. That is a strong application —
but it is not a slam dunk, and a firm hiring at $150–190k for a role with "Azure Local" in the
title will probe it in the first technical screen. Go in with the answer in §2.1 ready.

---

## 3. What changed in this rewrite

- **Reordered Overhead Door** so the VMware→Hyper-V migration, S2D, and failover clustering are
  the first three bullets. Previously they were fourth, fifth, and buried.
- **Reframed Smart Shared Services as consulting**, not voice engineering. That role is your only
  client-facing delivery experience and the JD lists it under Preferred. It was previously
  written as a technical role that happened to have clients.
- **Cut from Village Communities:** the Avaya migration, Crystal Reports, VOIP call-quality fix,
  PeopleSoft/Yardi. Good material, irrelevant here. Kept the Hyper-V consolidation, the Director
  scope, and the JD Edwards conversion (evidence of leading a major migration with an executive).
- **Skills regrouped** so Virtualization & HCI leads and Windows Server is second — the two
  categories this JD is built on.
- Location line now reads **"Columbus, Ohio (Remote)"** since the posting is remote.

---

## 4. Two things I inferred — check them

- **Cluster Shared Volumes and live migration** are listed under Skills. You didn't name them,
  but you cannot operate a Hyper-V failover cluster without both, so I treated them as implied.
  The JD names them explicitly, so they need to be there. Confirm you're comfortable being
  questioned on them.
- **OCI read as Oracle Cloud Infrastructure**, spelled out on the resume. Correct me if not.

---

## 5. Make LinkedIn match before you apply

This matters more than usual because AHEAD says outright that their tooling looks for
inconsistencies against available information. Your LinkedIn is the available information.

Two specific mismatches to fix on **LinkedIn**, not on the resume:

1. **Village Communities shows two roles both starting Jul 2011** — "System Administrator"
   (to Aug 2017) and "IT Director" (to Apr 2017). Identical start dates read as an error to a
   parser and as overlapping employment to a checker. Either set the real promotion date or
   merge them into one entry, matching how the resume now reads.
2. **Your LinkedIn About says you're seeking "Director, Senior Management, Architect, Senior
   Engineer, or Program Management."** You're applying for a Senior Technical Consultant role.
   A recruiter who opens your profile sees five targets, none of which is this one. Rewrite it
   toward hybrid infrastructure and Hyper-V, or at minimum add Consultant to the list.

Also worth adding to LinkedIn, since none of it is there and all of it is now on your resume:
Nutanix, Storage Spaces Direct, vSAN, SCVMM, Windows Admin Center, FortiGate, F5, OCI, Windows
Event Forwarding. Right now your resume is substantially richer than your profile, and that
asymmetry is itself a signal worth removing.

---

## 6. Still needed from you

- [ ] **Phone number**
- [ ] **Columbus State** — degree or program, and year (or say the word and I'll drop the year)
- [ ] Any **certifications**, current or in progress (see §2.6 — this is the highest-value gap
      you can close quickly)
- [ ] Any exposure to **Azure Arc, Azure Migrate, Azure Monitor, Azure Policy, or Defender for
      Cloud** — even lab or pilot work is worth a line

---

## 7. Two more things about this application

**Don't use the AI opt-out.** The JD offers one, but it routes you to the General Application
with the role written in a free-text field. That's a worse path than being read by their
screener — your resume is keyword-dense and well matched, which is exactly the input an
automated first pass rewards.

**Write a cover letter for this one.** Normally optional; here it's the mechanism for addressing
the Azure Local gap on your own terms rather than letting a screener find it. Three short
paragraphs: the VMware→Hyper-V migration you led, the S2D and failover clustering you run, and
one direct sentence about closing the Arc and Azure Local gap. Say the word and I'll draft it.
