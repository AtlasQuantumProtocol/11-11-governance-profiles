# 11/11 Governance Profile — CNSA 2.0 Target

Status: TARGET PROFILE  
Baseline Date: June 19, 2026

## Purpose

Define the national-security / DoD-facing maximum-assurance profile for Execution Governance.

This is a target profile, not yet the production-enforced profile.

## Current Production Profile

EA11_EVIDENCE_STATE_V2_2

ML-DSA-65: VALID  
SLH-DSA-SHA2-128f: VALID  
PQ Verification: VERIFIED  
PQ Enforcement: REQUIRED  

## CNSA 2.0 Target Profile

ML-DSA-87  
ML-KEM-1024  
LMS/XMSS for firmware and long-lived code signing  
HSM-held signing keys  
TEE runtime attestation  
Witnessed transparency ledger  
External anchoring  

## Profile Modes

COMMERCIAL_PROFILE  
ML-DSA-65 + SLH-DSA-SHA2-128f

DEFENSE_PROFILE  
ML-DSA-87 + SLH-DSA-SHA2-128f

NATIONAL_SECURITY_PROFILE  
ML-DSA-87 + ML-KEM-1024 + LMS/XMSS + HSM + TEE + Witnessed Ledger

## Acceptance Criteria

CNSA_2_0_PROFILE must not be marked ENFORCED until:

ML-DSA-87 is implemented  
ML-KEM-1024 is implemented  
HSM custody is implemented  
External transparency witnessing is implemented  
Independent review is complete  

Execution Governance™
