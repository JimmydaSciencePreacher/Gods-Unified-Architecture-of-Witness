# Physics Investigation I — Quantum Entanglement: Correlations Between Separated Quantum Systems

**Domain:** Physics  
**Survey position:** Investigation 1 of 5 in the Physics domain; Investigation 1 of 50 in the cross-disciplinary survey  
**Status:** Evidence-led investigation  
**Prepared:** 2026-11-18  
**Primary question:** How can spatially separated quantum systems exhibit correlations that cannot be reproduced by theories satisfying Bell's locality condition and the relevant auxiliary assumptions?

## 1. Purpose and scope

Quantum entanglement is an appropriate first physics investigation because it forces careful distinctions among a physical system, the mathematical state used to describe it, correlations among measurement outcomes, and interpretations of what those results mean.

The aim is not to use the word "strange" as an explanation. The aim is to identify the experimental phenomenon, the theorem that makes it testable, the results that have been observed, and the conclusions those results do and do not warrant.

This document focuses on entanglement and Bell tests. It does not attempt to settle the interpretation of quantum mechanics, the ontology of the wavefunction, or the general problem of measurement.

## 2. What entanglement means

A composite quantum state is entangled when it cannot be represented as a product of independent states for its component systems. In the simplest pure-state case, a separable two-particle wavefunction can be written as a product:

\[
\psi(x,y)=\psi_1(x)\psi_2(y).
\]

An entangled state cannot be written in that form. For a pair of spin-one-half particles, a familiar example is the singlet state:

\[
|\psi^-\rangle=\frac{1}{\sqrt{2}}\left(|\uparrow\downarrow\rangle-|\downarrow\uparrow\rangle\right).
\]

If both particles' spins are measured along the same direction, the outcomes are perfectly anti-correlated: one is up when the other is down. Before measurement, quantum theory does not describe each particle as simply carrying its own independent pure spin state. The joint state is the relevant description.

The singlet state is an illustrative model. Experimental entanglement can involve photons, ions, atoms, superconducting circuits, and other physical systems, with different degrees of freedom and measurement methods.

**Important distinction:** Entanglement is not merely the fact that two particles were once near each other or share a common origin. Classical systems can also be correlated by a shared history. The specifically quantum question is whether the observed correlations can be accounted for by the class of local hidden-variable models constrained by Bell's theorem.

## 3. Historical question: EPR and Schrödinger

In 1935, Albert Einstein, Boris Podolsky, and Nathan Rosen published an argument that challenged the completeness of the quantum-mechanical description. They considered distant systems whose measurement outcomes were strongly correlated and asked whether the theory omitted elements of physical reality.

Erwin Schrödinger responded to the EPR argument and introduced the term *entanglement* for the nonseparability of the joint quantum state. Schrödinger emphasized that the best possible description of a whole need not reduce to the best possible independent descriptions of each part.

The historical dispute was not simply "Einstein believed in determinism, quantum mechanics believes in randomness." Einstein's concern included locality and separability. Nor did EPR establish that quantum mechanics was experimentally false. It raised a question about whether the quantum description was complete.

## 4. Bell's theorem: turning a conceptual dispute into a test

In 1964, John Bell derived a result showing that theories satisfying a specified locality condition, together with auxiliary assumptions, must obey constraints on the statistical correlations of separated measurements. Quantum mechanics predicts that some entangled states and measurement settings violate those constraints.

A widely used form is the Clauser–Horne–Shimony–Holt (CHSH) inequality. In a local hidden-variable model satisfying the relevant assumptions, the CHSH parameter obeys:

\[
|S|\leq 2.
\]

Quantum mechanics predicts that appropriately prepared entangled states can reach:

\[
|S|\leq 2\sqrt{2}.
\]

The difference is experimentally testable. Repeated trials are required: a single pair's outcomes do not by themselves demonstrate a Bell inequality violation. Researchers compare the statistical correlations across many measurement settings and trials.

Bell's theorem does not show that every conceivable hidden-variable theory is impossible. It excludes theories satisfying the conditions used to derive the inequality. Nonlocal hidden-variable approaches, such as Bohmian mechanics, are not excluded merely by Bell-inequality violations. The exact assumptions and scope of each theorem and experiment must be stated.

## 5. What a Bell-test experiment does

A typical Bell test proceeds in broad outline:

1. A source prepares pairs of entangled quantum systems.
2. One member of each pair is sent to measurement station A; the other goes to station B.
3. Each station chooses a measurement setting.
4. Each station records an outcome.
5. The process is repeated over many trials.
6. The joint statistics are used to calculate a Bell parameter and compare it with the relevant inequality.

The measurement settings must be selected and implemented in a way that addresses the assumptions of the test. In particular, the experiment must address whether information could pass between the stations during a trial and whether losses or selective detection could distort the sample.

A Bell test is therefore not just a demonstration that two detectors produce matching or opposite results. It is a carefully designed statistical experiment.

## 6. Experimental record

### 6.1 Early tests and the loophole problem

Experiments by John Clauser and collaborators, Alain Aspect and collaborators, and others progressively tested Bell inequalities. Early results supported quantum predictions, but practical limitations left possible loopholes. Two especially important issues were:

- **Locality or communication loophole:** Could a signal or other causal influence travel between measurement stations quickly enough to affect the outcomes?
- **Detection loophole:** Could undetected particles or events bias the sample of recorded results?

A result is only as strong as the experimental design and the assumptions justified by that design. The history of Bell tests is partly a history of progressively closing these loopholes.

### 6.2 Loophole-free tests in 2015

In 2015, independent experiments reported Bell-inequality violations while simultaneously closing the major locality and detection loopholes. The Stanford Encyclopedia of Philosophy's Bell theorem review describes these experiments and their significance. These results established that the observed correlations cannot be explained by local hidden-variable models satisfying the assumptions tested.

### 6.3 Tests with superconducting circuits in 2023

A 2023 *Nature* experiment demonstrated a loophole-free Bell-inequality violation using superconducting circuits. The researchers deterministically entangled a pair of qubits connected through a cryogenic link spanning 30 metres, performed randomly selected high-fidelity measurements, and analyzed more than one million trials. They reported:

\[
S=2.0747\pm0.0033,
\]

with a reported p-value smaller than \(10^{-108}\). This is a measured statistical violation of the local bound of 2 in that experimental arrangement. It is not a direct measurement of a signal travelling faster than light.

The experiment is important because Bell violations are not restricted to optical photon experiments; they can also be demonstrated in superconducting quantum circuits.

### 6.4 Nobel recognition

The 2022 Nobel Prize in Physics was awarded jointly to Alain Aspect, John Clauser, and Anton Zeilinger for experiments with entangled photons that established the violation of Bell inequalities and advanced quantum information science.

The Nobel scientific background document provides a detailed account of entangled states, the EPR debate, Bell tests, and applications.

## 7. What the experiments establish

The experimental record supports the following conclusions:

1. Entangled quantum systems exhibit correlations that violate Bell inequalities.
2. Loophole-free experiments have ruled out the relevant class of local hidden-variable explanations under the assumptions of those tests.
3. The effect is reproducible across different physical platforms, including photons, atomic systems, and superconducting circuits.
4. Entanglement is a usable resource in quantum information science, including quantum communication, quantum cryptography, and quantum computation.
5. A classical common-cause account satisfying Bell locality cannot reproduce all the observed correlations.

The results are not merely philosophical speculation. Bell inequalities connect a precise theoretical distinction to measurable statistical outcomes.

## 8. What the experiments do not establish

Careful boundaries are essential:

- **No faster-than-light messaging:** Entanglement does not provide a controllable channel for sending a message faster than light. Local measurement outcomes are individually random; the nonclassical pattern becomes visible when records are compared through ordinary communication.
- **No proof that consciousness causes collapse:** Bell-test violations do not establish that a human mind creates the measurement result.
- **No rejection of every hidden-variable theory:** The tests rule out the specified local class, not every possible realist or hidden-variable interpretation.
- **No single settled interpretation:** The operational predictions of quantum mechanics are extraordinarily successful, but interpretations differ on what the quantum state represents and what measurement means.
- **No universal claim that all distant objects are entangled in a practically useful way:** Entanglement is a precise property of a quantum state and can be degraded by interactions with the environment.
- **No conclusion that spatial separation is irrelevant in every physical respect:** Relativistic causal structure remains essential to the design and interpretation of experiments.

## 9. Decoherence and practical fragility

Entanglement is not a magical bond immune to its surroundings. Interactions with uncontrolled environmental degrees of freedom can cause decoherence, making coherent quantum correlations harder to preserve and observe.

This is one reason entanglement experiments require carefully controlled sources, isolation, detectors, timing, and measurement procedures. Quantum technologies must generate, distribute, manipulate, and verify entanglement under real physical constraints.

Decoherence should not be casually equated with every interpretation of wavefunction collapse. It is a physical process in which correlations with an environment suppress observable interference in a system considered by itself. The interpretation of measurement remains a broader question.

## 10. Applications: from foundational physics to information science

Entanglement is a resource in quantum information theory. Applications include:

- **Quantum teleportation:** Transfer of an unknown quantum state using shared entanglement plus classical communication. It does not transport matter or allow faster-than-light communication.
- **Quantum key distribution:** Certain protocols use quantum correlations to detect eavesdropping or support security under explicitly stated assumptions.
- **Entanglement swapping:** Entanglement can be established between systems that did not directly interact, through a joint measurement on other systems.
- **Quantum computing:** Entanglement can contribute to computational capabilities and correlations among qubits; its role depends on the algorithm and architecture.

These applications are not all equivalent and should be investigated separately when the Computer and Information Science domain is reached.

## 11. Questions this investigation opens

1. What is the most precise physical meaning of the quantum state?
2. How should quantum measurement be understood?
3. Which assumptions are required for a given Bell inequality and experimental design?
4. How do entanglement and decoherence interact in realistic systems?
5. How can entanglement be generated, preserved, distributed, and verified over longer distances?
6. What limits the practical performance of quantum networks?
7. How do different interpretations of quantum mechanics account for the same experimentally verified correlations?
8. What is the relationship between entanglement, spacetime, and relativistic quantum field theory?

These questions do not all have the same scientific status. Some are engineering problems; others are foundational and interpretive questions.

## 12. Cross-disciplinary relevance

This investigation has natural connections to other domains in the fifty-study survey:

- **Information science:** Entanglement as a resource for quantum communication and computation.
- **Mathematics:** Hilbert spaces, tensor products, probability, inequalities, and correlation functions.
- **Materials science:** Superconducting circuits and engineered quantum devices.
- **Astronomy and particle physics:** Tests of quantum correlations in high-energy and long-baseline settings.
- **Thermodynamics:** The relationship between entanglement, entropy, information, and physical resources.

A connection is not proof that the disciplines share one mechanism. Each transfer must be made with the definitions and evidence appropriate to the receiving field.

## 13. GUA-W placement: questions, not imported conclusions

This case can be placed alongside existing GUA-W questions concerning relationship, distinction, measurement, registration, and the difference between a system and a description of that system.

However:

- Quantum entanglement is not being declared equivalent to GUA-W's concept of joining.
- A Bell correlation is not being declared evidence of spiritual connection.
- Quantum measurement is not being equated with Witness.
- A quantum state is not being equated with the Word.
- Bell's theorem does not establish a theological conclusion.

The scientific investigation is allowed to illuminate questions. It does not author or revise the GUA-W architecture.

## 14. Triple Constraint disposition

**Biblical compliance:** The scientific findings are not used as proof-texts or as evidence that Scripture secretly teaches quantum mechanics. No theological doctrine is derived from entanglement.

**Scientific coherence:** The account distinguishes entangled joint states, Bell inequalities, experimental violations, locality assumptions, detection limitations, no-signalling, and interpretive questions. Numerical claims are tied to the cited experiment. The conclusions are limited to the tested classes of models and stated assumptions.

**GUA-W consistency:** The investigation is placed alongside existing questions without adding a new layer, Gear, runtime stage, State term, or universal law. Scientific concepts are not renamed as GUA-W concepts.

**Disposition: PASS within the stated scope.** The experimental phenomenon and Bell-test results are well established. The interpretation of quantum mechanics remains an active foundational subject.

## 15. Sources and further reading

1. The Royal Swedish Academy of Sciences / Nobel Committee for Physics. (2022). *Scientific Background on the Nobel Prize in Physics 2022*. Official scientific background document. https://www.nobelprize.org/uploads/2026/05/advanced-physicsprize-2022-5.pdf
2. Stanford Encyclopedia of Philosophy. *Bell's Theorem*. Substantive revision January 25, 2024. https://plato.stanford.edu/entries/bell-theorem/
3. Stanford Encyclopedia of Philosophy. *Quantum Entanglement and Information*. Substantive revision May 2, 2023. https://plato.stanford.edu/entries/qt-entangle/
4. Storz, S., et al. (2023). “Loophole-free Bell inequality violation with superconducting circuits.” *Nature*, 617, 265–270. https://doi.org/10.1038/s41586-023-05885-0
5. Giustina, M., et al. (2013). “Bell violation using entangled photons without the fair-sampling assumption.” *Nature*, 497. https://doi.org/10.1038/nature12012

## Conclusion

Quantum entanglement is not simply two particles behaving alike. It is a property of a joint quantum state whose correlations cannot be reproduced by local hidden-variable models satisfying Bell's conditions.

The evidence is experimental, quantitative, and replicated across different physical platforms. It has also become technologically useful.

The strange part is real; the exaggerations often attached to it are not.

**One physical phenomenon. Precise mathematical constraints. Repeated experimental witnesses. Interpretations kept distinct from measurements.**
