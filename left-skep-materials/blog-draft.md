---
title: "Fictitious Commodities of the Mind: Polanyi, AI, and the Double Movement"
date: 2026-04-08
categories: [AI, political economy, labour]
draft: true
---

In *The Great Transformation*, Karl Polanyi argued that the extension of market logic into domains where it doesn't naturally belong — land, labour, money, recast as "fictitious commodities" — provokes a spontaneous counter-movement from society to protect itself. The first movement is commodification; the second is protection. The welfare state, labour law, financial regulation — all products of the second movement.

Polanyi's "labour" was implicitly *bodily* labour. The disembedding of physical human effort from social relations, its repackaging as something buyable by the hour. The protective counter-movement — factory acts, working time regulations, safety legislation — was correspondingly about protecting bodies from the market.

AI extends the commodification logic to a domain Polanyi never considered because it wasn't technically possible: the outputs of professional cognition.

```{mermaid}
%%| label: fig-double-movement
%%| fig-cap: "Polanyi's double movement: physical labour (19th–20th C) vs cognitive labour (21st C)"
flowchart LR
    subgraph Physical["<b>Physical Labour (Polanyi)</b>"]
        direction TB
        P1["Labour disembedded\nfrom social relations"] --> P2["Commodification\n(wage labour by the hour)"]
        P2 --> P3["Bodily harm\n& immiseration"]
        P3 --> P4["Counter-movement:\nfactory acts, unions,\nwelfare state"]
    end

    subgraph Cognitive["<b>Cognitive Labour (AI update)</b>"]
        direction TB
        C1["Professional cognition\ndisembedded from credentials"] --> C2["Commodification\n(outputs produced by compute)"]
        C2 --> C3["Credential devaluation\n& status threat"]
        C3 --> C4["Counter-movement:\nIP expansion, licensing,\nregulatory capture?"]
    end
```

## The credentialing moat

This matters because the professional class historically understood itself as *protected from* commodification precisely through its credentialing and expertise. The entire architecture of professionalisation — medical boards, bar associations, chartered statuses, doctoral requirements — was constructed to create artificial scarcity around cognitive labour, keeping it embedded in guild-like social structures rather than exposed to raw market logic.

AI doesn't just commodify mental labour generically. It attacks the *decommodification mechanisms* that the professional class built over two centuries. This is not analogous to factory workers facing a new machine. It is analogous to factory workers facing a new machine that also dissolves their union simultaneously.

## Elite overproduction as pre-existing condition

Peter Turchin's structural-demographic model suggests the Western world — particularly the US and UK — was already deep into an elite overproduction cycle before generative AI arrived. Credential inflation, expanding graduate populations competing for a shrinking pool of elite positions, rising intra-elite competition, declining returns to education. All pre-2022 trends.

AI lands directly on the occupational categories where surplus elites have been parking themselves: knowledge work, content production, consulting, analysis, junior professional roles. The people most vocally opposed to AI aren't the traditional working class. They are the credentialed precariat — journalists, academics, illustrators, copywriters, junior lawyers. These are precisely Turchin's frustrated elite aspirants.

On this reading, AI operates as an *accelerator* of an existing structural-demographic pattern rather than an *initiator*. The hostility it generates from the credentialed class isn't really about AI's properties. It's the political expression of a group whose status and livelihood were already under structural threat, experiencing an acute intensification of a chronic condition.

This also explains why the reaction tends towards moral vocabulary — AI as *theft*, as *exploitation*, as an offence against *craft* and *authenticity* — rather than careful policy analysis. That's what you'd expect from threatened status groups. The moral framing is doing status-defence work.

```{mermaid}
%%| label: fig-causal-chain
%%| fig-cap: "AI as accelerator: from elite overproduction to the second movement"
flowchart TD
    A["Elite overproduction\n(pre-existing trend:\ncredential inflation,\ndeclining returns to education)"] --> B["AI arrives\n(accelerator, not initiator)"]
    B --> C["Credential moat collapses\n(professional cognition\ncommodified)"]
    C --> D["Moral-vocabulary backlash\n('theft', 'exploitation',\n'authenticity')"]
    C --> E["Matthew Effects\n(gains concentrate with\ncapital holders)"]
    D --> F{"Second movement"}
    E --> F
    F -->|Protective| G["Regulatory capture,\nguild restoration,\nincumbent defence"]
    F -->|Emancipatory| H["Open-source AI,\ndemocratised access,\nredistribution"]
```

## The political coding of AI attitudes

Something peculiar has happened to the politics of technology. AI enthusiasm has become culturally coded as part of a package: overlapping with crypto, with Musk fandom, with a particular flavour of techno-optimism that reads as libertarian and masculine. Scepticism has become coded as progressive, aligned with concerns about labour, extraction, and corporate power.

This is historically anomalous. The left was broadly pro-technology for most of the twentieth century — electrification, industrialisation, the NHS's embrace of computing, the post-war faith in planning through better information. There is even a specifically left-utopian tradition — Keynes's "Economic Possibilities for our Grandchildren," Srnicek and Williams's *Inventing the Future*, Bastani's *Fully Automated Luxury Communism*, Iain M. Banks's Culture novels — that sees technological abundance as the material precondition for liberation from wage labour.

But this strand is remarkably quiet in current discourse. The FALC position requires a longer time horizon and a more speculative disposition than the immediate material struggles of the creative precariat can sustain. If your commissions are being lost to Midjourney, an argument that automation will eventually produce post-scarcity requires a level of abstraction that is hard to maintain.

There is also an awkward bedfellow problem. "AI will create abundance that should be redistributed" sounds uncomfortably close to Sam Altman's UBI-funded-by-AGI pitch. The left has reasons to distrust that framing, and the reasons relate to a gap between potential and realisation.

## The Kaldor-Hicks gap

The Kaldor-Hicks efficiency criterion says a change is efficient if the winners *could* compensate the losers and still come out ahead. Crucially, it does not require that compensation actually happens.

The entire history of industrial transformation suggests it usually doesn't. The enclosure of the commons, industrialisation, financialisation, platform capitalism — in each case the surplus was real but the compensation mechanism had to be fought for over decades, through union organisation, political conflict, and genuine social crisis.

This is where Polanyi's double movement becomes predictive rather than merely descriptive. The first movement — commodification of cognitive labour — is producing concentration. Matthew Effects: to him that hath shall be given. AI capability accrues to those with capital, data, and talent to deploy it. Productivity gains flow to firm owners, not displaced workers. This is already visible.

The second movement — redistribution as a stability response — is what historically produces welfare states, labour protections, antitrust action. But it emerges *reactively*, from elite fear of instability rather than from benevolence. Bismarck's social insurance was counter-revolutionary strategy. The New Deal was a response to systemic crisis. The post-war European settlement followed the same pattern.

The uncomfortable implication: the FALC endpoint might actually require passing *through* a period of intensified inequality and instability severe enough to force the political realignment. The Altman pitch — "trust us, we'll redistribute" — isn't so much wrong as naively ahistorical about the mechanism. The redistribution probably comes, but through conflict, not through anyone's charitable foundation.

## What the second movement might look like

If the first Polanyian movement was the commodification of physical labour, and the second movement produced regulation of working conditions, hours, and safety, then the commodification of cognitive labour should produce a second movement with a different character.

Some possibilities are already visible: intellectual property expansion, licensing requirements for AI systems, mandatory human-in-the-loop regulations, credentialing bodies reasserting gatekeeping functions. The EU AI Act's risk-tiering approach and professional bodies' early attempts to regulate AI use in medicine, law, and accounting are plausibly early second-movement phenomena.

But there is a darker possibility. The professional class's counter-movement might succeed in *protecting incumbents* through regulatory capture rather than producing broadly beneficial social protection. That would be a second movement in form but not in Polanyian spirit — guild restoration rather than societal self-defence. The history of occupational licensing in the US suggests this is not merely hypothetical.

Beverly Silver's *Forces of Labor*, which applies Polanyi's framework to successive waves of industrialisation, would predict that the counter-movement follows capital mobility with some regularity but possibly with a lag and in forms we don't yet recognise. Fred Block and Margaret Somers have argued that the post-1980 marketisation wave constitutes a new first movement whose counter-movement remains incomplete. Nancy Fraser has extended the double movement into a *triple* movement — adding emancipation alongside marketisation and protection — which matters here because some AI opposition is protective (defend existing jobs) while some is emancipatory (democratise access, break monopolies), and these can conflict.

## The sorting

```{mermaid}
%%| label: fig-sorting
%%| fig-cap: "Material position → platform → affect → analytical framework"
flowchart TD
    subgraph Position["<b>Material position</b>"]
        CP["Credentialed precariat\n(journalists, academics,\nillustrators, junior professionals)"]
        TE["Technical-capital elite\n(founders, engineers,\ninvestors)"]
    end

    subgraph Platform["<b>Platform</b>"]
        BS["Bluesky"]
        X["X"]
    end

    subgraph Affect["<b>Affect</b>"]
        SK["Scepticism / hostility"]
        EN["Enthusiasm / optimism"]
    end

    subgraph Framework["<b>Analytical framework</b>"]
        LF["Labour, extraction,\ncorporate power,\nauthenticity"]
        TF["Abundance, acceleration,\ntechno-optimism,\ne/acc"]
    end

    CP --> BS --> SK --> LF
    TE --> X --> EN --> TF
```

The Bluesky/X divergence that prompted this post is, on this analysis, downstream of a broader sorting. Bluesky concentrated the frustrated aspirant-elite class — journalists, academics, cultural producers — whose structural position was already deteriorating. X retained more of the capital-holding and technical elite for whom AI represents opportunity. It looks like an ideological divide about technology, but it's more parsimoniously explained as a material-interest divide expressing itself through technological attitudes.

The genuinely uncomfortable conclusion is that both the progressive anti-AI position and the techno-optimist pro-AI position may be largely *rationalised class interest*, with the analytical frameworks chosen to fit the material situation rather than the other way round. Which doesn't make either position wrong — but it suggests the discourse is less about AI's actual properties than about pre-existing distributional conflicts that AI has brought to a head.

Polanyi would not have been surprised.