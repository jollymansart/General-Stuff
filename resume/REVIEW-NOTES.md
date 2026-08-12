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

### 5a. Village Communities — resolved, and it improved the resume

You were **hired in as Director of IT**, not promoted into it. The split entry was a LinkedIn
character-limit workaround, not two jobs.

The resume now reads **IT Director, Jul 2011 – Aug 2017**, single entry, with "Hired to run IT
for the organization and owned it outright." That's a cleaner and stronger claim than the
promotion story I had assumed — six unbroken years of directorship instead of an ambiguous
dual title.

**Fix LinkedIn to match:** delete the "System Administrator" entry entirely and keep one
IT Director role, Jul 2011 – Aug 2017. If the description runs past the character limit, cut
the bullets rather than splitting the job — a truncated description costs you nothing, and a
duplicated role costs you a verification flag.

### 5b. The About section — I'd go higher than you're aiming

You're right that the five-title list has to go. But **"Senior IT Administrator" swings too far
the other way.** It's below your current scope, below the IT Director role you held for six
years, and below the job you're applying for. A recruiter comparing that headline against a
$150–190k Senior Technical Consultant posting sees a mismatch in the wrong direction — and
undershooting reads as a lack of confidence, which is harder to recover from than overshooting.

**Stop shopping for a title and describe the capability instead.** Any of these work:

> Hybrid infrastructure engineer — Hyper-V, VMware, Storage Spaces Direct, and Windows Server
> at enterprise scale. I run 500+ servers across three hypervisors and led our migration off
> VMware onto Hyper-V.

> Enterprise virtualization and Windows infrastructure. Hyper-V, VMware, hyper-converged
> storage, Active Directory, and PowerShell automation across a 500+ server multi-site estate.
> Former IT Director; comfortable owning a budget and a migration plan at the same time.

Neither names a target title, so neither can mismatch a posting. Both say what you do at a
level consistent with the roles you want. The second one is better if you're also open to
leadership roles, because it puts the Director experience in play without asking for it.

Whichever you use, drop "I am an active go-getter." It's the first line a recruiter reads.

Also worth adding to LinkedIn, since none of it is there and all of it is now on your resume:
Nutanix, Storage Spaces Direct, vSAN, SCVMM, Windows Admin Center, FortiGate, F5, OCI, Windows
Event Forwarding. Right now your resume is substantially richer than your profile, and that
asymmetry is itself a signal worth removing.

---

## 6. Still needed from you

- [x] ~~Columbus State~~ — resolved, see §8
- [ ] **Phone number** — the only remaining blocker on both documents
- [ ] Any **certifications**, current or in progress (see §2.6 and §8 — now the highest-value
      thing you can do for this application)
- [ ] Any exposure to **Azure Arc, Azure Migrate, Azure Monitor, Azure Policy, or Defender for
      Cloud** — even lab or pilot work is worth a line

---

## 7. Two more things about this application

**Don't use the AI opt-out.** The JD offers one, but it routes you to the General Application
with the role written in a free-text field. That's a worse path than being read by their
screener — your resume is keyword-dense and well matched, which is exactly the input an
automated first pass rewards.

**The cover letter is written** — `Cover-Letter-AHEAD.md`. Its job is to address the Azure Local
gap on your terms rather than letting a screener discover it, so the third paragraph names the
gap outright and says what you'd do about it. That paragraph is the whole reason the letter
exists; if you trim anything, don't trim that.

Two notes on it. The opening skips the throat-clearing and leads with the migration, because
that's the sentence that earns the next paragraph. And it closes on documentation, since your
posting raises it three separate times — deliverables, knowledge transfer, and success
criteria — which is unusually heavy weighting and worth answering directly.

Fill in the phone number, and check the tone sounds like you before it goes.

---

## 8. No degree — and for this posting, it genuinely does not matter

**Read the Required Qualifications again.** They open with "Five or more years of experience
designing, implementing, or supporting enterprise compute and virtualization environments" and
never mention education. Not a degree, not "or equivalent experience," not a preference under
Preferred Qualifications either. AHEAD wrote eleven required bullets and none of them is a
diploma. You have seventeen years against a five-year bar.

This is normal in infrastructure. Nobody staffing an Azure Local migration asks where the
consultant went to school; they ask whether the cluster came up.

### How it's written

> **Columbus State Community College** — Computer Science coursework: C, COBOL, Assembler, JCL,
> Visual Basic, AS/400 CL

That is honest and complete. "Coursework" claims attendance and nothing more — it does not imply
a degree, and no reader takes it as one.

Three deliberate omissions:

- **No dates.** Years on an unfinished program invite arithmetic and answer nothing useful.
- **No "1.5 years," no "did not graduate."** You are not required to volunteer incompleteness,
  and doing so would be the only line on two pages arguing against you. Omitting it is not a
  misrepresentation; announcing it is self-sabotage.
- **No apology or explanation.** The section is two lines at the bottom of page two and should
  read as a fact, not a confession.

Listing the coursework is what turns a thin line into a substantive one — it shows CS
fundamentals rather than a bare institution name. The languages themselves (COBOL, JCL,
Assembler, AS/400 CL) are irrelevant to Hyper-V work, and that's fine; they're doing structural
work here, not keyword work.

**Never soften this in an interview.** If asked, "I did computer science coursework at Columbus
State and went to work instead of finishing" is a complete answer. Say it in a normal tone and
move to the next question. Seventeen years of production infrastructure is the credential, and
you are talking to people who know that.

### What this does change: certifications

With no degree, **certifications become the only formal credential on the page — and you have
none.** They're listed under Preferred Qualifications, so this is the single highest-value gap
you can close, and it's now doing double duty.

**AZ-800 and AZ-801** (Windows Server Hybrid Administrator) map almost exactly onto the Azure
Local gap in §2 — hybrid AD, Azure Arc, failover clustering, Windows Admin Center. Passing them
closes the technical gap and the credential gap with one effort.

Even "AZ-800 in progress, exam scheduled [month]" on the resume changes the read. It converts
the gap from something a screener finds into something you're visibly acting on. AHEAD also
sponsors certifications outright, which means they've already decided this is how people on
their bench get qualified — you'd be arriving pointed in the direction they were going to send
you anyway.

Book the exam and tell me the date; I'll add the line to both documents.
