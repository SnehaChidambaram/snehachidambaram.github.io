---
layout: default
---

<header>
    <nav>
        <ul>
            <li><a href="/" class="active">Home</a></li>
            <!-- <li><a href="/assets/sneha_CV_06_24.pdf">CV</a></li> -->
        </ul>
    </nav>
</header>
<style>
    /* body { font-family: Arial, sans-serif; line-height: 1.6; }
    .index { width: 100%; border-collapse: collapse; }
    .index td { border: 1px solid #ddd; padding: 10px; }
    .index tr:nth-child(even) { background-color: #f2f2f2; } */
    .highlight { background-color: #ffff99; } /* Highlighting style */
    /* a { color: #0077cc; } */
</style>
<!-- new stuff -->
<!-- Master table -->
<table class="index">
  <tbody>
    <tr style="padding:0px">
      <td style="padding:0px">

        <!-- Introduction -->
        <table class="index" id="intro-table">
          <tbody>
            <tr style="padding:0px">
              <td style="width:63%;vertical-align:middle;">
                <p style="text-align:center">
                  <h1 style="text-align: center;">
                    Sneha Chidambaram
                  </h1>
                </p>
              </td>
              <td>
              </td>
            </tr>
            <tr style="padding:0px">
              <td style="width:63%;vertical-align:top">
                <p>
                  Welcome to my page! I'm Sneha, a junior at Dublin High studying chemical biology in the context of cancer research. During my sophomore chemistry class, I began questioning why matter interacts the way it does, and being an aspiring physician I was drawn to study the chemistry of living things.
                </p>
                <p>
                 Glycosylation is one of the most compositionally advanced and combinatorially diverse types of post-translational modifications. In fact, I was surprised to learn that due to the macro- and micro-heterogeneity of glycan attachment on peptides, many proteomics researchers decide to exclude them from their analytes altogether! As an aspiring oncologist-glycobiologist, <highlight>I see carbohydrate chemistry and proteomics as two sides of the same coin</highlight> – quantifiable alterations to cells’ glycosylation patterns clearly do not occur at random, and the search for a sugar trail in the language of cell surface glycans must carry forth as we attempt to elucidate molecular drivers of disease.

                </p>
                <p>
                  You can also find me on <a href="https://twitter.com/snehachid_108" target="_blank" rel="noreferrer noopener">Twitter</a>.
                </p>
              </td>
              <td style="max-width:30%;vertical-align:text-top;padding-left:3%">
                <a href="/assets/images/profile_picture.jpg" id="profile_picture"><img alt="profile_picture" title="Sneha Chidambaram" src="/assets/images/profile_picture.jpg"></a>
              </td>
            </tr>
          </tbody>
        </table>

        <!-- newsfeed -->
        <!-- <h2>Newsfeed</h2>
        <p>Placeholder text</p>
        <table>
          <thead>
            <tr>
              <th>date</th>
              <th>description</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>(2022-07-07)</td>
              <td>placeholder text!</td>
            </tr>
          </tbody>
        </table>
        <br>-->

        <!-- Research interests -->
        <h2>Research Tracks</h2>
        Here are 3 tracks of research I'm excited about working on, and a few open questions I had while doing some readings.
        <table class="index">
            <tbody>
                <tr class="highlight">
                    <td>
                        <h3>Track 1: Cancer Cell Biology</h3>
                        <ol>
                            <li>Explain the sequence of mutations required to divide without apoptosis, and contrast it with the sequence of mutations required to divide without shortening the coding regions of DNA.</li>
                            <li>How were CAR T Cells engineered/personalized for Emily Whitehead, a 6 year old with acute lymphoblastic leukemia (ALL), who was completely cured?</li>
                            <li>Why do unhealthy cells develop aberrant glycoproteoforms on their cell surface?</li>
                            <li>How might we design a degrader target for the ubiquitin-proteasome pathway that is not susceptible to pharmacological resistance by cancer cells?</li>
                            <li>How can we get cells surrounding cancer cells to “snitch” on the cancer cell by detecting biomarkers that might indicate a tissue’s getting way denser than it normally would?</li>
                        </ol>
                    </td>
                </tr>
                <tr>
                    <td>
                        <h3>Track 2: Neurodegenerative Disorders</h3>
                        <ol>
                            <li>How does the downstream impact of misfolded tau proteins differ from the impact of misfolded alpha synuclein?</li>
                            <li>Can misfolded proteins cooperatively promote the aggregation of other misfolded proteins?</li>
                            <li>Is there a characteristic state of improper folding that differentiates intrinsically disordered regions from the general average?</li>
                            <li>How can the ability to conserve spatial and charge density in ion mobility spectrometry help with analyzing glycosylated intrinsically disordered proteins?</li>
                            <li>How does disordered post-translational folding impact glycosylation, and vice versa?</li>
                        </ol>
                    </td>
                </tr>
                <tr class="highlight">
                    <td>
                        <h3>Track 3: Cardiovascular Pharmacology</h3>
                        <ol>
                            <li>How does beta-arrestin modulate the effects of beta-adrenergic receptor signaling in cardiac cells, particularly in the context of heart rate and blood pressure regulation?</li>
                            <li>How does biased signaling through beta-adrenergic receptors influence cardiac function differently when mediated by beta-arrestin versus G-protein signaling pathways?</li>
                            <li>Would the selective activation of beta-arrestin over G-protein pathways in beta-adrenergic receptors provide a therapeutic advantage in treating conditions like hypertension?</li>
                            <li>What are the mechanistic pathways by which beta-arrestin interacts with beta-adrenergic receptors to slow down heart rate, and how can these pathways be targeted pharmacologically?</li>
                            <li>In what ways can manipulating beta-arrestin signaling in beta-adrenergic receptors lead to novel treatments for cardiac arrhythmias and what are the potential risks?</li>
                        </ol>
                    </td>
                </tr>
            </tbody>
          </table>

        <!-- Publications and projects -->
        <table class="index">
          <tbody>

            <!-- pub -->
            <!-- <tr>
              <td class="project-media">
                <img class="project-img" src="/assets/images/screen.jpg" alt="alt" title="title">
              </td>
              <td class="project-info">
                <span class="project-title">A Benchmark Framework for Evaluating Structure-to-Sequence Models for Protein Design</span>
                <br>
                Jeffrey Chan, <highlight>Sneha Chidambaram</highlight>, David Brookes, Sam Sinai
                <br>
                <input type="checkbox" id="trigger3">
                [<label for="trigger3"><a id="fakelink">abstract</a></label>]
                <span id="box">
                  Abstract here.
                </span> /
                [<a href="/" target="_blank" rel="noreferrer noopener">proposal</a>] /
                [<a href="https://newscience.org/2022-summer-fellows/" target="_blank" rel="noreferrer noopener">press release</a>]
                <p></p>
                <p>
                  Blurb.
                </p>
              </td>
            </tr> -->

            <!-- pub -->
            <tr>
              <td class="project-media">
                <img class="project-img" src="/assets/images/schematic.png" alt="schematic" title="schematic">
              </td>
              <td class="project-info">
                <span class="project-title">A review of bispecific proximity based therapeutics for inhibiting cancer cell proliferationh</span>
                <br>
                <highlight>Sneha Chidambaram*</highlight>
                <br>
                <i>Drafting a preprint review article</i> (2024)
                <br>
                <input type="checkbox" id="trigger2">
                <p></p>
                <p>
                  Cancer cells adversarially exploit signal transduction pathways, survival adaptations, and transcriptional drivers to promote their survival, immune resistance, and proliferation. Targeted protein degradation (TPD) has emerged as a promising alternative to small molecule inhibitors, using degraders to induce transient associations between proteins and degradation machinery, leading to degradation mediated by the proteasome or lysosome. PROTACs target intracellular proteins, while LYTACs and TICTACs address extracellular and tumor-associated proteins, respectively. This review explores the mechanisms, interactions, and challenges of these degraders, highlighting their potential to overcome resistance and expand the druggable proteome. Our idea is  Understanding the factors influencing targeted protein degradation efficacy, such as protein properties, linker design, degradation signals, cellular machinery, and context, is crucial for advancing next-generation cancer therapies.
                </p>

              </td>
            </tr>



          </tbody>
        </table>

        <!-- Acknowledgements -->
        <h2>Acknowledgements</h2>
        <p>
          My webpage uses open source code by <a href="https://seyonechithrananda.github.io/" target="_blank" rel="noreferrer noopener">Seyone Chithrananda</a>, which is built on <a href="https://www.kianfaizi.com/" target="_blank" rel="noreferrer noopener">Kian Fazi</a>'s template and inspired by Jon Barron.
        </p>
        <br>

        <!-- Mentors -->
        <!-- <h2>Mentors</h2>
        <p>
          <br>- Amma, Sri Mata Amritanandamayi Devi ~ a world renowned humanitarian and Chancellor, Amrita University
        </p> -->


      </td>
    </tr>

  </tbody>
</table>
