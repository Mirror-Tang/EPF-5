# EPF-5

Ethereum Protocol Fellowship Cohort 5 - Experience sharing on ZK Security

# Circom Audit Learning

## Week 1

### Objectives:

Master Circom syntax

Familiarize with the Circom and Snarkjs development toolchain to write, test code, and generate target files

Learn to write Circom circuits using Tornado Cash as an example

### Study Tasks:

Read the official documentation of the Circom circuit language

Read the 0xPARC Circom study section

Get familiar with the circom + snarkjs toolchain and the online development platform zkrepl provided by iden3

Learn Circom circuit writing using Tornado Cash as an example

### Github:

Deeply understand the principles of the Tornado Cash project

Explore other zk projects based on Circom, such as:

Dark Forest

Semaphore

### Extension:

Understand the application prospects of ZK technology in the web3 industry

## Week 2

### Objectives:

Understand the responsibilities of a zk audit engineer

Familiarize with common zk circuit vulnerabilities and proof system vulnerabilities

Learn to use auditing tools

### Study Tasks:

Read "Security of ZKP projects: same but different"

Read the 0xPARC ZK Bug Tracker

Read audit reports, currently focusing on Circom projects

Learn to use auditing tools like PICUS and CODA

## Week 3

### Objectives:

Further understand ZK security

### Study Tasks:

Learn through puzzles in ZKHack, which involve more proof systems such as STARK, not just limited to SNARK

### Learn through puzzles in ZKCTF:

Ingonyama CTF

Metatrust CTF ZKPlus

## ZK Risk Level Description

<table>
  <tr>
    <td>Risk level</td>
    <td>Description</td>
  </tr>
  <tr>
    <td>High Risk</td>
    <td>The issue can lead to substantial financial, reputation, availability, or privacy damage.</td>
  </tr>
    <tr>
    <td>Medium Risk</td>
    <td>The issue can lead to moderate financial, reputation, availability, or privacy damage. Or the issue can lead to substantial damage under extreme and unlikely circumstances.</td>
  </tr>
    <tr>
    <td>Low Risk</td>
    <td>The issue does not pose an immediate security threat, but may be a lack of following best practices or more easily lead to the future introductions of bugs.</td>
  </tr>
    <tr>
    <td>Informational</td>
    <td>Information not relevant to security, but may be helpful for efficiency, costs, etc..</td>
  </tr>
</table>

## Circuit Check List

<table>
  <tr>
    <td>Classification</td>
    <td>Description</td>
  </tr>
  <tr>
    <td>Completeness Check</td>
    <td>Completeness Check</td>
  </tr>
    <tr>
    <td>Soundness Check</td>
    <td>Underconstrained input/output signal  |  Underconstrained component  |  Arithmetic operation correctness check  |  Bit length check(Range check) </td>
  </tr>
    <tr>
    <td>Knowledge Leakage</td>
    <td>Trusted Setup Leakage  |  Public information leakage privacy  </td>
  </tr>
    <tr>
    <td>Architeture Design</td>
    <td>E.g. H(x)=y with limited value of x</td>
  </tr>
</table>


