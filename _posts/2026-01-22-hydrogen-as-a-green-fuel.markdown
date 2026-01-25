---
layout: post
title:  "Hydrogen as a green fuel"
date:   2026-01-25 10:00:24 +0000
---
Hydrogen is a highly combustible element which produces no harmful emissions when used as a fuel. It is the most abundant element in the universe; however, due to its extreme reactivity, it is often found in compounds and not immediately ready for use. Hydrogen is termed green when it is produced from renewable energy resources by electrolysis, electricity is used in an electrolyser to separate hydrogen and oxygen in water. In contrast, hydrogen produced by steam methane reforming may be considered grey if the waste carbon monoxide is released into the atmosphere or blue if it is captured and stored. 

# Hydrogen opportunities and challenges

Green hydrogen could offer a low-carbon solution to the heating sector's current emissions in the UK. Hydrogen gas would be something consumers are more familiar with than heat pumps if used in boilers, given that 78.6% of households currently use mains gas for heating. A gradual transition could be carried out using hydrogen too, since it can be blended with methane. Maintaining the need for a gas distribution network for domestic consumers by switching from natural gas to hydrogen, rather than solely utilising heat pumps, would also secure existing jobs. 

## Production and use

Hydrogen is flexible once it has been produced since not only can it be combusted in a similar manner to natural gas for heat, it can also be used in fuel cells to generate electricity. A fuel cell reverses the reaction carried out for electrolysis, combining hydrogen and oxygen to produce water. Hydrogen could serve the energy needs of almost every industry, transport, heating and aviation being examples. 

## Natural gas and hydrogen blends

Where hydrogen is blended with methane (the main component in natural gas), the extent of hydrogen blend in a combustion environment is limited, dependent on the technology used; while a boiler designed for 100% hydrogen combustion would work without issues, boilers designed to work with hydrogen blends typically have limitations for hydrogen content. These limitations are a result of the vastly different heating values associated with each compound, dictating specific design parameters for each type of boiler. Hydrogen also has a much lower energy per unit volume, so more gas needs to be transported and combusted to generate the same amount of heat as methane: this can become a challenge, whereby more energy is required to compress, store, and move the hydrogen.

Figure 1 displays that the relationship between carbon dioxide emissions and the fraction of hydrogen in a gas blend is non-linear, meaning that the reduction in emissions is not the same percentage as the increase in hydrogen in the blend. This is a direct result of the different combustion characterstics of the two gases and can be explained by the following section, with a example of a 50% hydrogen, 50% methane blend calculated.

### The chemistry behind hydrogen blends

Two reactions occur when a hydrogen/methane blend is combusted, this is described for each element by:

$\mathrm{CH_4(g) + 2O_2(g) \rightarrow CO_2(g) + 2H_2O(g)}$

$\mathrm{2H_2(g) + O_2(g) \rightarrow 2H_2O(g)}$

<p align="center">
Table 1. Element characteristics for the reactions.
</p>

| Element              | Molar mass (g/mol) | Δh<sub>comb</sub> (kJ/mol) |
|:--------------------:|:-----------------:|:-------------------------:|
| Hydrogen (H₂)        | 2.016             | 241.83                    |
| Methane (CH₄)       | 16.04             | 802.34                    |
| Carbon dioxide (CO₂)| 44.01             | —                         |
| Oxygen (O₂)          | 16.00             | —                         |

The molar fraction of the gas blend is 

$x_{H_2}=\frac{n_{H_2}}{n_{H_2}+n_{CH_4}}$.

The mass relationship in terms of grams for 1 mole is 

$(16)CH_4+(64)2O_2\rightarrow(44)CO_2+(18)2H_2O$.

The number of moles of methane required to produce 1 kWh when combusted is 

$n_{CO_2}=\frac{E}{\Delta h_{comb}}=\frac{60\times60}{802.34}=4.49\ \text{moles}$.

The mass of carbon dioxide produced based on the molar fraction is 

$M_{CO_2}=\frac{n_{CO_2}M_{CO_2}}{1000}=\frac{4.49\times44.01}{1000}=0.198\ \text{kg}$.

The CO₂ reduction relationship for a 50\% hydrogen blend is evaluated using the energy contributions per component:

$\Delta h_{H_2}=241.83\times0.5=120.915\ \text{kJ/mol}$
$\Delta h_{CH_4}=802.34\times0.5=401.17\ \text{kJ/mol}$.

The total energy contribution for 1 mole of hydrogen blend is 

$\Delta h_{total}=\Delta h_{CH_4}+\Delta h_{H_2}=401.17+120.915=522.085\ \text{kJ/mol}$.

The energy difference between 1 mole of methane and 1 mole of hydrogen blend is 

$802.34-522.085=280.255\ \text{kJ/mol}$.

The additional moles of hydrogen blend required to make up the energy deficit are 

$\frac{280.255}{522.085}=0.537$, giving a total of $1+0.537=1.537$ moles.

The contribution of methane is 

$0.5\times1.537=0.7685$.

The resulting CO₂ emissions are 

$0.198\times0.7685=0.152\ \text{kg}$.

This method can be used to extrapolate the curve in Figure 1.

<p align="center">
  <img src="/assets/images/h2blend2.svg" alt="Hydrogen blend">
</p>

<p align="center">
Figure 1. Effect of hydrogen fraction in a hydrogen and methane gas blend.
</p>

## Hydrogen safety

Hydrogen is a very small element, meaning that it is more prone to leaks when compared with other hydrocarbon-based gases. Expensive leak-sensing equipment and modifications, due in part to leaks but also hydrogen embrittlement, to existing gas equipment are required where hydrogen is to replace natural gas. At present, gas network operators in the UK are preemptively replacing iron mains gas pipes with hydrogen-safe polyethylene pipes, to remove the barrier of hydrogen embrittlement. The explosion risk for hydrogen is much more significant than natural gas, too, due to the prevalence of leaks and the higher flammability range from 4-75% compared to methane at around 5-15% by volume in air.

# Summary

Hydrogen exists as an option to solve the UK's energy requirements in presently polluting sectors. Thus far, hydrogen rollouts for domestic heating and transportation have been extremely limited when compared to electrification, with infrastructure such as refuelling stations being sparse and a domestic supply of hydrogen not existing. In addition to this, hydrogen produced by electrolysis and steam methane reforming with carbon capture and storage accounted for less than 1% of hydrogen produced in 2023. This suggests that at present, if demand for hydrogen increased, there would not be adequate green fuel sources to meet the demand.
