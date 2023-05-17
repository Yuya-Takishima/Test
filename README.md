# Test

asdasdasd

## Test2
  
asdasdasdasdasdasd

### Test3

[#test1](#test)
[#test2](#test2)
[#test3](#test3)

asdasdasdasdasdasd

```mermaid

flowchart LR

AA[Phantom Design]

A[Marker <br>Extraction]--->B[Marker <br>Matching]
B[Marker <br>Matching]--->C[Field <br> Calculation] & E[Automated <br>reporting]
C[Field <br> Calculation]-->D[Spherical Harmonic <br>Analysis]
D[Spherical Harmonic <br>Analysis]-->E[Automated <br>reporting];
D[Spherical Harmonic <br>Analysis]-->F[Distortion Correction]

click AA "https://acrf-image-x-institute.github.io/mri_distortion_toolkit/phantom_notes.html"
click A "https://acrf-image-x-institute.github.io/mri_distortion_toolkit/marker_extraction.html"
click B "https://acrf-image-x-institute.github.io/mri_distortion_toolkit/marker_matching.html"
click C "https://acrf-image-x-institute.github.io/mri_distortion_toolkit/field_calculation.html"
click D "https://acrf-image-x-institute.github.io/mri_distortion_toolkit/fit_spherical_harmonics.html"
click E "https://acrf-image-x-institute.github.io/mri_distortion_toolkit/reporting.html"

```

```mermaid
  flowchart TD;
      A["link test (open in same tab)"]
      B["link test (open in new tab)"]
      C[anchor test]
      D[mailto test]
      E[other protocol test]
      F[script test]
      TITLE --> A & B & C & D & E & F
      click A "https://mermaid-js.github.io/mermaid/#/" _self
      click B "https://mermaid-js.github.io/mermaid/#/" _self
      click C "#test2" _self
      click D "mailto:user@user.user" "mailto test"
      click E "notes://do-your-thing/id" "other protocol test"
      click F "javascript:alert('test')" "script test"

```
