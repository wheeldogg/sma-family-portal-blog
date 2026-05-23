---
layout: page
title: "Conference Report — 5th International SMA Congress, Budapest 2026"
permalink: /congress-report-budapest-2026/
---

<style>
.conference-report-figure {
  margin: 2rem 0;
  text-align: center;
}
.conference-report-figure img {
  max-width: 100%;
  height: auto;
  border-radius: 10px;
  box-shadow: 0 6px 18px rgba(0,0,0,0.12);
}
.conference-report-figure figcaption {
  margin-top: 0.65rem;
  font-size: 0.95rem;
  color: #555;
}
.conference-report-gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1rem;
  margin: 1.5rem 0 2.25rem;
}
.conference-report-gallery figure {
  margin: 0;
}
.conference-report-gallery img {
  aspect-ratio: 4 / 3;
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 8px;
  box-shadow: 0 4px 14px rgba(0,0,0,0.12);
  cursor: zoom-in;
}
.conference-report-gallery figcaption {
  margin-top: 0.4rem;
  font-size: 0.82rem;
  color: #666;
}
.conference-report-lightbox {
  position: fixed;
  inset: 0;
  z-index: 1000;
  display: none;
  align-items: center;
  justify-content: center;
  padding: 1.5rem;
  background: rgba(0,0,0,0.88);
}
.conference-report-lightbox.is-open {
  display: flex;
}
.conference-report-lightbox img {
  max-width: min(96vw, 1400px);
  max-height: 88vh;
  width: auto;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 12px 36px rgba(0,0,0,0.45);
}
.conference-report-lightbox button {
  position: absolute;
  top: 1rem;
  right: 1rem;
  width: 2.5rem;
  height: 2.5rem;
  border: 0;
  border-radius: 50%;
  background: rgba(255,255,255,0.95);
  color: #111;
  font-size: 1.75rem;
  line-height: 1;
  cursor: pointer;
}
</style>

<div class="conference-report-lightbox" id="conference-report-lightbox" aria-hidden="true">
  <button type="button" aria-label="Close expanded image">&times;</button>
  <img src="" alt="">
</div>

# Conference Report for SMA Ireland

<figure class="conference-report-figure">
  <img src="{{ '/assets/images/congress-budapest-2026/budapest-sunrise.jpg' | relative_url }}" alt="Budapest skyline at sunrise during the 5th International Scientific Congress on SMA in March 2026">
  <figcaption>Budapest at sunrise during the 5th International Scientific Congress on SMA.</figcaption>
</figure>

**5th International Scientific Congress on SMA**
**Budapest, March 11–14, 2026**
**Attendee:** Shane Whelan (parent, SMA Ireland member)
**Date:** April 27, 2026

---

## Key Messages

1. **The congress was primarily scientific.** Much of the programme focused on biomarkers, treatment response, newborn screening, fatigue, respiratory care, animal models, and what still remains unknown in SMA.
2. **Advocacy and networking were the biggest practical benefit from my perspective.** Wednesday's advocacy meetings, informal conversations, and links with other European organisations gave useful context for SMA Ireland.
3. **Treatment access varies across Europe.** Risdiplam, dual therapy, adult access, and generic availability came up in several conversations, but they were one strand of a much broader congress rather than the whole focus.
4. **Ireland has strengths to build on.** It was encouraging to see Ireland broadly aligned with Scotland on newborn screening timing, with useful learning from UK representatives about the practical challenges of rollout.
5. **Generic and international pricing issues are worth tracking.** Conversations around lower-cost risdiplam routes in China and generic availability in India highlighted how quickly the access landscape can change globally.
6. **Practical family care matters as much as formal treatment pathways.** Play as physiotherapy, emergency planning, respiratory routines, and equipment choice were recurring themes with direct value for families.
7. **Further follow-up is needed on research language and funding.** SMA is often discussed alongside motor neuron biology, but the exact framing matters for advocacy, research funding, and public understanding.

---

## 1. Conference Overview

I attended the 5th International Scientific Congress on SMA in Budapest (March 11–14, 2026) as a parent and SMA Ireland member. The congress was organised by SMA Europe and brought together clinicians, researchers, pharmaceutical companies (Roche, Biogen, Novartis, Scholar Rock), advocacy organisations, and SMA families from across Europe.

The main purpose of the conference was scientific. There were detailed talks on biomarkers, newborn screening, laboratory research, clinical measurement, fatigue, respiratory care, rehabilitation, treatment strategy, and the next questions researchers are trying to answer.

I attended with a parent's perspective, so my own experience naturally shaped what I noticed. I was interested in treatment access, including questions around risdiplam and combination therapy, but I do not want to present the conference as being mainly about our family's situation. The strongest value for me was the mix of scientific context, advocacy meetings, and personal conversations with people working on SMA across Europe.

<figure class="conference-report-figure">
  <img src="{{ '/assets/images/congress-budapest-2026/report/2026-03-12-133319.jpg' | relative_url }}" alt="Conference slide from a Thursday advocacy meeting outlining current SMA treatments">
  <figcaption>A treatment overview slide from one of the Thursday advocacy meetings, setting out current SMA treatment options.</figcaption>
</figure>

## 2. Day-by-Day Summary

### Tuesday 10 March 2026 — Arrival, Budapest Context, and First Impressions

The day before the main congress sessions was arrival and orientation time in Budapest. These photos capture the city context around the week: the Danube, Buda, the Chain Bridge area, Fisherman's Bastion, and the first evening views that framed the congress trip.

{% assign day_2026_03_10 = "2026-03-10-114324.jpg,2026-03-10-134056.jpg,2026-03-10-134136.jpg,2026-03-10-134141.jpg,2026-03-10-134219.jpg,2026-03-10-134700.jpg,2026-03-10-134823.jpg,2026-03-10-165929.jpg,2026-03-10-165934.jpg,2026-03-10-170756.jpg" | split: "," %}
<div class="conference-report-gallery">
{% for image in day_2026_03_10 %}
<figure>
  {% assign image_path = "/assets/images/congress-budapest-2026/report/" | append: image %}
  <img src="{{ image_path | relative_url }}" alt="Budapest SMA Congress report image {{ image | remove: '.jpg' }}">
  <figcaption>{{ image | remove: ".jpg" }}</figcaption>
</figure>
{% endfor %}
</div>

### Wednesday 11 March 2026 — Opening Sessions, Advocacy, and Practical Family Support

Wednesday was an advocacy-focused start to the congress. The morning was particularly useful for connection-building and informal networking with people from SMA Europe, SMA UK, Italy, and other organisations, as well as conversations around treatment access and generic availability.

Two sessions stood out. One was about play as physiotherapy and how children can be supported to engage physically through enjoyable activities rather than only formal exercises. The other was the Italian session on emergency practices and family training, including the kind of practical approach shown in SAPRE's ["My Kid's Got Wheelz"](https://www.fsma.pl/wp-content/uploads/2017/06/invitation_mf4r_2017-ENGLISH.pdf) programme. Overall, Wednesday was a very good start to the conference because it grounded the week in lived experience, practical care, and European advocacy relationships.

{% assign day_2026_03_11 = "2026-03-11-143907.jpg,2026-03-11-151951.jpg,2026-03-11-163218.jpg,2026-03-11-163220.jpg,2026-03-11-164120.jpg,2026-03-11-170232.jpg,2026-03-11-171545.jpg" | split: "," %}
<div class="conference-report-gallery">
{% for image in day_2026_03_11 %}
<figure>
  {% assign image_path = "/assets/images/congress-budapest-2026/report/" | append: image %}
  <img src="{{ image_path | relative_url }}" alt="Budapest SMA Congress report image {{ image | remove: '.jpg' }}">
  <figcaption>{{ image | remove: ".jpg" }}</figcaption>
</figure>
{% endfor %}
</div>

### Thursday 12 March 2026 — Research Sessions, Biomarkers, Fatigue, and Evening Budapest

Thursday moved deeper into the scientific programme. A lot of the technical discussion was about biomarkers, NMR metabolomics, fatigue, animal models, and what should be measured beyond motor scores. Some talks included lay summaries, which helped make the more technical material easier to bring back into family and advocacy discussions. There was also detailed research around current therapies, including Spinraza/nusinersen, but I did not hear as much that day about new gene therapies for adults as I had expected.

From my side, the advocacy conversations around access and international practice remained very important, including risdiplam and dual therapy questions. The evening photos are included as part of the same day-by-day record after a walk around the city.

{% assign day_2026_03_12 = "2026-03-12-101956.jpg,2026-03-12-102146.jpg,2026-03-12-102152.jpg,2026-03-12-104013.jpg,2026-03-12-105711.jpg,2026-03-12-110219.jpg,2026-03-12-110812.jpg,2026-03-12-111909.jpg,2026-03-12-112318.jpg,2026-03-12-132111.jpg,2026-03-12-132944.jpg,2026-03-12-133319.jpg,2026-03-12-133810.jpg,2026-03-12-143014.jpg,2026-03-12-143754.jpg,2026-03-12-144339.jpg,2026-03-12-144356.jpg,2026-03-12-144844.jpg,2026-03-12-213118.jpg,2026-03-12-213125.jpg" | split: "," %}
<div class="conference-report-gallery">
{% for image in day_2026_03_12 %}
<figure>
  {% assign image_path = "/assets/images/congress-budapest-2026/report/" | append: image %}
  <img src="{{ image_path | relative_url }}" alt="Budapest SMA Congress report image {{ image | remove: '.jpg' }}">
  <figcaption>{{ image | remove: ".jpg" }}</figcaption>
</figure>
{% endfor %}
</div>

### Friday 13 March 2026 — Clinical Evidence, Respiratory Care, Paediatric Strategy, Posters, and Closing Reflections

Friday began with a beautiful sunrise over Budapest and continued with more proposed scientific studies, clinical discussions, poster presentations, and final reflections. The posters were useful for seeing where the research and real-world evidence are moving, including material on risdiplam and dual therapy, while still keeping the broader scientific programme in view.

{% assign day_2026_03_13 = "2026-03-13-062118.jpg,2026-03-13-062120.jpg,2026-03-13-062123.jpg,2026-03-13-062127.jpg,2026-03-13-090646.jpg,2026-03-13-091110.jpg,2026-03-13-091503.jpg,2026-03-13-092135.jpg,2026-03-13-092312.jpg,2026-03-13-092518.jpg,2026-03-13-093235.jpg,2026-03-13-093348.jpg,2026-03-13-114235.jpg,2026-03-13-115915.jpg,2026-03-13-120912.jpg,2026-03-13-121228.jpg,2026-03-13-122345.jpg,2026-03-13-134456.jpg,2026-03-13-141551.jpg,2026-03-13-143631.jpg,2026-03-13-145745.jpg,2026-03-13-150654.jpg,2026-03-13-152938.jpg,2026-03-13-155035.jpg,2026-03-13-155052.jpg,2026-03-13-155236.jpg,2026-03-13-170505.jpg,2026-03-13-170514.jpg,2026-03-13-170519.jpg,2026-03-13-182119.jpg" | split: "," %}
<div class="conference-report-gallery">
{% for image in day_2026_03_13 %}
<figure>
  {% assign image_path = "/assets/images/congress-budapest-2026/report/" | append: image %}
  <img src="{{ image_path | relative_url }}" alt="Budapest SMA Congress report image {{ image | remove: '.jpg' }}">
  <figcaption>{{ image | remove: ".jpg" }}</figcaption>
</figure>
{% endfor %}
</div>

## 3. Treatment Access and Dual Therapy: Evidence and Practice Discussed at the Congress

Dual therapy was not the whole focus of the SMA Europe congress, but it was one of the practical access questions I was deliberately trying to understand. My takeaway is that **combination therapy for SMA is no longer theoretical in some European centres, and the evidence base is continuing to develop**.

The following data points were presented and discussed at the congress. I have not independently verified all of these against source papers — they should be checked before being cited externally:

- **RESPOND trial** (Biogen, published in *Journal of Clinical Investigation*, Sept 2025): 95% of children who received nusinersen after Zolgensma showed motor improvements. NfL levels (a biomarker for neuronal injury) dropped 70–78%, confirming ongoing biological benefit.
- **Stanford presymptomatic cohort** (MDA 2025): All 8 infants who received Zolgensma within 2 months of birth — the best possible scenario — eventually required additional therapy. All improved after receiving it.
- **US multicenter case series** (MDA 2026): 19 patients across 6 centres received risdiplam after Zolgensma. All 14 assessed for motor function improved.
- **Systematic review** (Bemanalizadeh et al., *European Journal of Pediatrics*, 2025): 19 published studies and 6 ongoing trials. No additive toxicity signals in any combination.
- **Risdiplam is now on the WHO Essential Medicines List** — making it one of the most broadly endorsed treatments in the world.

There were also wider access conversations around risdiplam outside the child post-Zolgensma context. In particular, availability for adults over 18 appears to remain a problem in the Netherlands and elsewhere. This makes it important to treat risdiplam access as a broader European policy issue, not only as a question affecting one family or one subgroup.

## 4. European Practice vs Ireland

A gap between Ireland and several other European countries was something I encountered repeatedly in conversations at the congress:

- **France**: French neuromuscular centres appear to be prescribing dual therapy in practice. I spoke with Dr. Suzanne Quijano-Roy and Dr. Marta Gomez-Garcia de la Banda (APHP Paris), both of whom confirmed this is their practice for children showing plateau or suboptimal response after Zolgensma. *(I have not independently verified the formal regulatory/approval status — this reflects what I was told in conversation.)*
- **Germany**: A Roche Medical Science Liaison I spoke with at the congress indicated dual therapy is being prescribed on a case-by-case basis.
- **Italy** has strong SMA advocacy infrastructure — their model of comprehensive family support was presented as a benchmark for other countries.
- **USA**: A 2023 Cure SMA community survey was cited at the congress, reporting 12.4% of US SMA patients on combination therapy in real-world practice, with 82% of families citing "wanting access to all possible treatments" as motivation. *(Verify against Cure SMA source before citing externally.)*
- **Ireland's HSE MAP** currently restricts risdiplam to monotherapy — excluding children who received Zolgensma unless they meet "non-success" criteria (documented decline in motor scores or respiratory function). This framework was established before much of the current evidence existed, so it would be useful for SMA Ireland to keep the review of access criteria on the agenda.
- **Generics and international pricing** also came up informally. Risdiplam appears to be much less expensive in China, and generic routes in India were discussed as part of the wider global access landscape. These points would need careful verification before being used in formal advocacy, but they show why international monitoring matters.

## 5. Roche Engagement

As part of the wider access conversations, I spoke directly with a Roche MSL at the congress. Key points:

- Dual therapy is "the exception, not the rule" in Germany, but it is happening
- Roche is collecting real-world outcome data on combination therapy
- They committed to providing Ireland-specific information on risdiplam access
- Named Patient access may be possible through the treating consultant
- The conversation was constructive — Roche are aware of the Irish situation and did not dismiss the possibility of expanded access

This was useful context, but it should sit alongside the broader scientific and advocacy learning from the congress rather than define the whole report.

## 6. Networking & Contacts

| Contact | Organisation | Relevance |
|---------|-------------|-----------|
| Roche MSL | Roche | Ireland data, Named Patient pathway |
| Portia | SMA UK | Advocacy, UK rollout and treatment-access perspective |
| Christian Morris | SMA Europe | European coordination, policy |
| Suzanne Quijano-Roy | Neuromuscular specialist | Clinical expertise, French consultation |
| Marta Gomez-Garcia de la Banda | APHP Paris | French clinical perspective |
| Hannah McLoughlin | CHI Ireland | Irish clinical team |
| SMA Italy representatives | Famiglie SMA | European coalition, advocacy model |

## 7. Emerging Science

### NMR Metabolomics in SMA

New research is linking SMA to glucose and lipid metabolism — suggesting the disease's effects extend beyond motor neurons into whole-body metabolic function. This could provide new biomarkers beyond NfL for monitoring treatment response, help explain the fatigue and energy issues SMA patients experience daily, and eventually lead to metabolic interventions alongside existing treatments.

The biomarker discussions were detailed, but they also made clear that this area is still developing. There is still a lot that is not known about which markers will be reliable, how they should be used in routine care, and how they should influence treatment decisions.

<figure class="conference-report-figure">
  <img src="{{ '/assets/images/congress-budapest-2026/inspiration-slide.jpg' | relative_url }}" alt="Conference slide highlighting key themes and ideas emerging from the SMA congress">
  <figcaption>The congress balanced hard science with a sense that new ideas are steadily opening up more options for families.</figcaption>
</figure>

### Sensorimotor Function & Fatigue

<figure class="conference-report-figure">
  <img src="{{ '/assets/images/congress-budapest-2026/sma-effort-fatigue.jpg' | relative_url }}" alt="Conference slide from the SMA EFFORT study on proximal predominant fatigability and how fatigue affects function in SMA">
  <figcaption>Fatigue came through as a serious and under-measured part of life with SMA, and this was one of the clearest examples presented.</figcaption>
</figure>

The SMA Effort study and research into proximal predominant fatigue (PPF) are examining the lived experience of SMA beyond standard motor function scores. Many SMA patients report significant fatigue that impacts daily life but isn't captured by standard clinical assessments like CHOP-INTEND or HFMSE. This research validates what families already know: our children get tired in ways the clinical numbers don't always reflect.

### Newborn Screening and RAINBOWFISH

The heel prick test and newborn screening came up as an important part of the wider treatment landscape. It was useful to hear how different countries are handling rollout and to see that Ireland is broadly comparable with Scotland's timeline, with Scotland having moved slightly earlier and the UK still dealing with some practical implementation issues.

RAINBOWFISH, a Roche-sponsored study of risdiplam in presymptomatic infants identified through newborn screening, is directly relevant to Ireland as screening becomes part of the pathway. The wider point is that earlier diagnosis changes the whole conversation: treatment, follow-up, biomarkers, and long-term monitoring all become more important.

### New Therapies and Future Approaches

<figure class="conference-report-figure">
  <img src="{{ '/assets/images/congress-budapest-2026/motor-neuron-replacement-slide.jpg' | relative_url }}" alt="Lay summary conference slide describing experimental motor neuron replacement and repair concepts in SMA research">
  <figcaption>Some of the more forward-looking talks touched on repair strategies that go beyond today's standard treatments.</figcaption>
</figure>

There was some discussion of newer and future therapies at the congress, including muscle-targeted and regenerative approaches, but from my perspective this was not one of the biggest themes of the week. I did not come away feeling that these emerging therapies were a major focus of conversation compared with biomarkers, access, practical care, and the day-to-day realities families are dealing with now.

Apitegromab (Scholar Rock) was one example mentioned — a selective anti-myostatin antibody working through a different mechanism than current SMN-enhancing treatments. It may become an important option in time, but for me it felt more like part of the wider background of where the field may be heading rather than one of the main practical takeaways from Budapest.

I did not hear as much about new gene therapies for adults as I had expected. A lot of the technical work seemed to be around understanding current treatments, studying Spinraza/nusinersen in laboratory and animal models, and identifying biomarkers that could help explain treatment response and disease progression.

Another point I want to follow up is how SMA is described in relation to motor neuron disease. SMA clearly involves motor neuron biology, but the overlap with broader motor neuron disease terminology needs to be handled carefully. Getting that language right may matter for research funding, public understanding, and advocacy.

## 8. Practical Care Insights

<figure class="conference-report-figure">
  <img src="{{ '/assets/images/congress-budapest-2026/cough-assist-ambu.jpg' | relative_url }}" alt="Conference slide about daily respiratory care in SMA, including questions about whether to carry a cough machine or AMBU bag">
  <figcaption>Practical respiratory care advice was one of the most immediately useful parts of the congress for family life at home.</figcaption>
</figure>

Useful takeaways for all Irish SMA families:

- **Cough assist protocols:** Ambu bag technique, salbutamol as adjunct, 35+/35- pressure settings
- **FES (Functional Electrical Stimulation):** Worth discussing with physiotherapy teams
- **Play as physiotherapy:** Using play, games, and enjoyable activity as part of practical physical engagement
- **Emergency practice:** Learning from European family-training models on respiratory and emergency planning
- **Guitar as therapy:** Fine motor exercise, especially for powered wheelchair users
- **iKarate:** Adapted martial arts programme — social + physical
- **Boccia:** Competitive sport option, great for inclusion
- **Finger lights:** Sensory and motor play tool for younger children
- **Equipment variety and community knowledge:** Seeing the range of equipment families brought to the event was useful in itself, and the community atmosphere made it easier to learn from what others are already doing day to day

## 9. Recommendations for SMA Ireland

1. **Keep treatment access criteria under review, including risdiplam.** The HSE MAP criteria and post-Zolgensma access questions remain important, but they should be framed as part of a wider treatment-access discussion that also includes adults over 18 and international practice.
2. **Continue European advocacy links.** SMA UK, SMA Europe, Italian representatives, and other organisations offered practical insight into how access, family support, and policy are being approached elsewhere.
3. **Track generic and international pricing developments carefully.** China and India were mentioned in conversations about lower-cost or generic risdiplam routes. These points need verification, but they are relevant to long-term access strategy.
4. **Share practical care learning with Irish families.** Play as physiotherapy, emergency planning, cough assist routines, respiratory supports, equipment choice, and adapted sport all have immediate value.
5. **Build on Ireland's newborn screening progress.** Ireland appears to be well placed compared with Scotland's rollout timeline, and there may be useful learning from UK implementation challenges.
6. **Clarify SMA research language for funding and advocacy.** It may be worth exploring how SMA is described in relation to motor neuron disease so that Irish advocacy is accurate, understandable, and useful for research funding.
7. **Consider sending a representative to future SMA Europe congresses.** The networking and informal learning alone were highly valuable.

## 10. Next Steps

Following the conference, I plan to:

- Share a balanced summary of the scientific, advocacy, and practical-care learning with SMA Ireland
- Follow up with European contacts made through SMA Europe, SMA UK, Italy, and the clinical community
- Continue gathering evidence on treatment access, including risdiplam, dual therapy, adult access, and international pricing
- Discuss our own family-specific clinical questions privately with our clinical team
- Explore whether specialist European consultation would be useful through appropriate routes
- Follow up with Roche for the Ireland-specific information they committed to providing

I'm happy to share any of my research, contacts, or evidence files with SMA Ireland to support advocacy efforts.

<figure class="conference-report-figure">
  <img src="{{ '/assets/images/congress-budapest-2026/chain-bridge-sunset.jpg' | relative_url }}" alt="Budapest's Chain Bridge at sunset on the Danube during the week of the SMA congress">
  <figcaption>An evening view of Budapest after the congress sessions — a fitting close to a valuable and hopeful week.</figcaption>
</figure>

---

**Shane Whelan**
SMA Ireland member
Parent advocate

<script>
(function () {
  var lightbox = document.getElementById('conference-report-lightbox');
  if (!lightbox) return;

  var expandedImage = lightbox.querySelector('img');
  var closeButton = lightbox.querySelector('button');

  function closeLightbox() {
    lightbox.classList.remove('is-open');
    lightbox.setAttribute('aria-hidden', 'true');
    expandedImage.src = '';
    expandedImage.alt = '';
  }

  document.querySelectorAll('.conference-report-gallery img').forEach(function (image) {
    image.setAttribute('tabindex', '0');
    image.addEventListener('click', function () {
      expandedImage.src = image.currentSrc || image.src;
      expandedImage.alt = image.alt || '';
      lightbox.classList.add('is-open');
      lightbox.setAttribute('aria-hidden', 'false');
    });
    image.addEventListener('keydown', function (event) {
      if (event.key === 'Enter' || event.key === ' ') {
        event.preventDefault();
        image.click();
      }
    });
  });

  closeButton.addEventListener('click', closeLightbox);
  lightbox.addEventListener('click', function (event) {
    if (event.target === lightbox) closeLightbox();
  });
  document.addEventListener('keydown', function (event) {
    if (event.key === 'Escape') closeLightbox();
  });
}());
</script>
