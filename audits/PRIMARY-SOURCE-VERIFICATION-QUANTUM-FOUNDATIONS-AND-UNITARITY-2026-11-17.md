# Primary-Source Verification — Quantum Foundations and Unitarity

**Review date:** 2026-11-17  
**Parent record:** [Evidence Audit — Diagnostic Case Trace 001: Quantum Foundations and Unitarity](EVIDENCE-AUDIT-Quantum-Foundations-and-Unitarity.md)  
**Historical source:** Original Diagnostic Case Trace 001, preserved unchanged in the original repository.  
**Scope:** Verify state-space representation, unitary evolution, entropy invariance, no-cloning, no-deleting, and the limits of claims about information persistence. This is a focused formal and literature review, not a claim that quantum mechanics establishes metaphysical persistence.

## 1. Executive assessment

**Status: PARTIAL — the standard formal results are sound within their assumptions; the broad inference to GUA-W AXIOM 001 is not established.**

The existing audit correctly distinguishes:
- closed-system unitary evolution;
- reduced dynamics of an open subsystem;
- invariance of von Neumann entropy under unitary conjugation;
- the no-cloning theorem for arbitrary unknown quantum states;
- the narrower no-deleting theorem for deleting one of two identical unknown copies while retaining the other.

An important qualification is added: **no-cloning and no-deleting do not mean that quantum states can never be erased, reset, measured, decohered, or transferred into environmental degrees of freedom.** The no-deleting theorem addresses a specific transformation on multiple copies. Ordinary erasure/reset is a different physical process and must be analyzed together with the apparatus and environment.

These theorems do not prove that information can never be modified, deleted, or rewritten in every sense, and they do not prove GUA-W AXIOM 001. The GUA-W comparison remains a bounded analogy, not a scientific verification.

## 2. Claim U-01 — State-space representation

In standard non-relativistic quantum mechanics, pure states are represented by rays in a complex Hilbert space; normalized state vectors are representatives of those rays. Mixed states are represented by density operators. A single ket is therefore not an adequate representation of every possible quantum state.

**Disposition:** PASS within the standard formalism; PARTIAL if the source trace treats every state as a single state vector.

## 3. Claim U-02 — Unitary time evolution

For a closed system with a self-adjoint Hamiltonian \(H\), the Schrödinger equation is

\[
i\hbar\frac{d}{dt}|\psi(t)\rangle=H|\psi(t)\rangle.
\]

For time-independent \(H\), the solution is

\[
|\psi(t)\rangle=U(t)|\psi(0)\rangle,\qquad
U(t)=e^{-iHt/\hbar},
\]

and \(U^\dagger U=UU^\dagger=I\). For a time-dependent self-adjoint Hamiltonian, the corresponding propagator is unitary under the usual conditions.

This preserves inner products and total probability for the closed system. The formal result is exact within the stated model; it is not a claim that every subsystem or every phenomenological process is itself described by a unitary map.

**Disposition:** PASS for closed-system unitary evolution under the stated assumptions.

## 4. Claim U-03 — Von Neumann entropy under unitary evolution

For a density operator,

\[
\rho(t)=U(t)\rho(0)U^\dagger(t).
\]

Unitary conjugation preserves the eigenvalues of \(\rho\). Since von Neumann entropy is

\[
S(\rho)=-\operatorname{Tr}(\rho\ln\rho),
\]

it follows that \(S(\rho(t))=S(\rho(0))\) for the same closed system under unitary evolution.

**Critical scope distinction:** The entropy of a subsystem can change when that subsystem becomes entangled with an environment, even when the combined system-plus-environment state evolves unitarily. The reduced density operator is obtained by tracing out environmental degrees of freedom, and its evolution need not be unitary. Therefore “entropy is conserved” must identify the system whose entropy is being discussed.

**Disposition:** PASS for the entropy of the closed state undergoing unitary conjugation; FAIL if generalized to every subsystem or every operational description.

## 5. Claim U-04 — No-cloning

**Primary sources**
- W. K. Wootters and W. H. Zurek, “A single quantum cannot be cloned,” *Nature* 299, 802–803 (1982): https://doi.org/10.1038/299802a0
- D. Dieks, “Communication by EPR devices,” *Physics Letters A* 92, 271–272 (1982): https://doi.org/10.1016/0375-9601(82)90084-6

The no-cloning theorem states that no single universal physical operation can perfectly copy every arbitrary unknown quantum state. The result follows from linearity (and is compatible with the unitary description of closed dynamics).

**Important boundary:** It does not forbid copying classical data, preparing multiple systems in a known state, or copying mutually orthogonal states when the relevant state is known to belong to that orthogonal set. It does not mean that all information is unique, localized, or immune to loss in every sense.

**Disposition:** PASS for the precise no-universal-perfect-cloning theorem; FAIL for metaphysical or unrestricted “nothing can ever be copied” wording.

## 6. Claim U-05 — No-deleting and the meaning of erasure

**Primary source:** Arun K. Pati and Samuel L. Braunstein, “Impossibility of deleting an unknown quantum state,” *Nature* 404, 164–165 (2000): https://doi.org/10.1038/35004532; preprint https://arxiv.org/abs/quant-ph/9911090

The no-deleting theorem addresses a specific task: given two copies of an arbitrary unknown quantum state, a physical operation cannot perfectly delete one copy while leaving the other copy intact and placing the deleted copy's system in a fixed blank state, with no residual dependence hidden in an ancillary system. The unknown-state information cannot simply be made to disappear by that proposed transformation.

**Do not overgeneralize:** This is not a prohibition on every form of erasure, reset, measurement, or loss of access to a state. The 2003 follow-up by Pati and Braunstein explicitly distinguishes deletion from erasure and discusses how information can be moved into an ancilla rather than annihilated:
https://doi.org/10.1016/S0375-9601(03)01047-8

**Disposition:** PASS for the specific no-deleting theorem; FAIL if used to claim that no quantum information can ever be erased from a subsystem, dissipated, or rendered inaccessible.

## 7. Claim U-06 — Physical erasure and thermodynamic cost

**Primary source:** Rolf Landauer, “Irreversibility and Heat Generation in the Computing Process,” *IBM Journal of Research and Development* 5(3), 183–191 (1961): https://doi.org/10.1147/rd.53.0183

Landauer analyzes the thermodynamic implications of logically irreversible computation and the physical implementation of reset-like operations. The key lesson is not that every information-processing operation necessarily destroys information or dissipates a fixed amount of heat. The logical operation, physical implementation, initial state distribution, and thermodynamic conditions matter.

A reset of a subsystem can discard correlations from the subsystem's local description while information about the prior state remains in correlations with an environment or apparatus. The correct accounting must include the degrees of freedom that carry away the information and the thermodynamic conditions of the operation.

**Disposition:** PASS as a foundational result about physical computation and logically irreversible operations under its assumptions; not a universal law that every measurement or information transfer has one fixed energy cost.

## 8. Claim U-07 — Does unitarity prove GUA-W AXIOM 001?

**Source claim:** Quantum unitarity demonstrates that information cannot be retroactively modified, deleted, or rewritten, thereby verifying GUA-W AXIOM 001.

**Assessment: FAIL as a scientific proof of AXIOM 001.**

Unitary evolution preserves the mathematical structure of a specified closed quantum state. The GUA-W axiom concerns evidential/authority order and prohibits a conclusion from overwriting its source witness. The two claims are not mathematically identical.

A bounded analogy may be drawn between:
- preservation of inner products and state-spectrum under a unitary transformation; and
- the importance of preserving provenance and not silently rewriting a prior record.

But the physical theorem does not establish the GUA-W authority hierarchy, a universal metaphysical persistence principle, or a rule against all forms of subsystem erasure or state change.

**Disposition:** The analogy may be retained as INTERPRETATION / PROPOSED. It is not a physical proof of the axiom.

## 9. Triple Constraint review

| Constraint | Assessment | Reason |
|---|---|---|
| Biblical compliance | NOT DETERMINED BY THIS PHYSICS REVIEW | Quantum formalism does not establish a Scriptural interpretation. |
| Scientific coherence | PARTIAL overall; narrow formal claims pass | Unitary evolution, entropy invariance, no-cloning, and no-deleting are valid within their exact scopes; broad claims about all information deletion are not. |
| GUA-W consistency | PROPOSED / UNRESOLVED as a substantive mapping | A provenance/preservation analogy is possible, but mathematical identity and proof of AXIOM 001 are not established. |

## 10. Corrected wording for future use

> For a closed quantum system evolving under a self-adjoint Hamiltonian, time evolution is unitary and preserves inner products, total probability, and the eigenvalues—and therefore the von Neumann entropy—of the density operator. The no-cloning theorem prohibits a universal perfect copier for arbitrary unknown quantum states. The no-deleting theorem prohibits a specific perfect deletion of one unknown copy while retaining another. These results do not prohibit every form of measurement, subsystem reset, erasure, or transfer of information into an environment. They provide precise examples of preservation and operational limits under defined conditions; they do not, by themselves, prove GUA-W AXIOM 001 or a universal metaphysical law of information persistence.

## 11. Remaining questions

1. Which exact property is compared with GUA-W: norm, inner product, density-operator spectrum, total-system information, provenance, or something else?
2. Is the comparison about mathematical reversibility, evidential integrity, or metaphysical persistence?
3. Which system boundary is being used: closed total system, open subsystem, detector, or environment?
4. Does the proposed analogy remain useful when subsystem erasure and environmental information transfer are included?
5. What independent Scriptural argument is intended to support the theological claim?

## 12. Provenance and final status

This pass verifies the core mathematical claims and selected primary results on no-cloning, no-deleting, and physical erasure. It does not constitute a complete survey of quantum information theory or a proof of metaphysical persistence. The original Diagnostic Case Trace 001 and completed GUA-W architecture remain unchanged.

**Final status: PARTIAL — standard quantum formalism and the scoped no-cloning/no-deleting results are supported; broad no-erasure and GUA-W proof claims are not established.**
