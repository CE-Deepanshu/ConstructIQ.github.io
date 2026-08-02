# IMPORTANT SUBJECTS
## 1. Engineering Mathematics
<div class="mermaid">
flowchart TD
    EM[Engineering Mathematics]
    EM --> LA[Linear Algebra]
    EM --> CA[Calculus]
    EM --> DE[Differential Equations]
    EM --> PS[Probability & Statistics]
    EM --> NM[Numerical Methods]
    EM --> VC[Vector Calculus]

    LA --> MAT[Matrices]
    LA --> EIG[Eigenvalues & Eigenvectors]

    CA --> LIM[Limits & Continuity]
    CA --> PD[Partial Derivatives]
    CA --> MM[Maxima-Minima]

    DE --> FODE[First Order DE]
    DE --> HODE[Higher Order Linear DE]

    PS --> MVS[Mean, Median, SD]
    PS --> DIST[Distributions]
    PS --> REG[Regression & Correlation]

    NM --> NR[Newton-Raphson]
    NM --> TRAP[Trapezoidal Rule]

    VC --> GRAD[Gradient]
    VC --> DIV[Divergence & Curl]
</div>

<script type="module">
  import mermaid from "https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs";
  mermaid.initialize({ startOnLoad: true });
</script>

## 2. Structural Engineering
<div class="mermaid">
flowchart TD
    SE[Structural Engineering]
    SE --> SOM[Strength of Materials]
    SE --> SA[Structural Analysis]
    SE --> RCC[Reinforced Concrete]
    SE --> STEEL[Steel Structures]

    SOM --> SS[Stress-Strain]
    SOM --> BMD[BMD/SFD]
    SOM --> BSHR[Bending & Shear Stress]
    SOM --> COL[Columns & Struts]
    SOM --> TOF[Theories of Failure]

    SA --> DET[Determinate Structures]
    SA --> ILD[Influence Lines]
    SA --> MDM[Moment Distribution]
    SA --> MATR[Matrix Methods]

    RCC --> LSD[Limit State Design]
    RCC --> BEAM[Beams & Slabs]
    RCC --> FTG[Columns & Footings]
    RCC --> PSC[Prestressed Basics]

    STEEL --> CONN[Bolted/Welded Connections]
    STEEL --> TMC[Tension & Compression Members]
    STEEL --> BEAMS[Beams & Plate Girders]
    STEEL --> PLAS[Plastic Analysis]
</div>

<script type="module">
  import mermaid from "https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs";
  mermaid.initialize({ startOnLoad: true });
</script>

## 3. Geotechnical Engineering
<div class="mermaid">
flowchart TD
    GE[Geotechnical Engineering]
    GE --> CLASS[Soil Classification & Properties]
    GE --> PERM[Permeability & Seepage]
    GE --> EFF[Effective Stress]
    GE --> CONS[Consolidation]
    GE --> SHEAR[Shear Strength]
    GE --> EARTH[Earth Pressure]
    GE --> FOUND[Foundation Engineering]

    CLASS --> LIMIT[Consistency Limits]
    CLASS --> GRAIN[Grain Size Distribution]

    PERM --> DARCY[Darcy's Law]
    PERM --> FLOWN[Flow Nets]
    PERM --> QS[Quick Sand Condition]

    EFF --> PRINC[Effective Stress Principle]
    EFF --> PWP[Pore Water Pressure]

    CONS --> TERZ[Terzaghi's Theory]
    CONS --> TIME[Time Factor & Settlement]

    SHEAR --> MC[Mohr-Coulomb]
    SHEAR --> TRIAX[Triaxial Test]

    EARTH --> RANK[Rankine Theory]
    EARTH --> COUL[Coulomb Theory]

    FOUND --> BC[Bearing Capacity]
    FOUND --> PILE[Pile Capacity]
    FOUND --> SLOPE[Slope Stability]
</div>

<script type="module">
  import mermaid from "https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs";
  mermaid.initialize({ startOnLoad: true });
</script>

## 4. Fluid Mechanics & Hydraulics
<div class="mermaid">
flowchart TD
    FM[Fluid Mechanics & Hydraulics]
    FM --> PROP[Fluid Properties & Statics]
    FM --> KIN[Kinematics]
    FM --> DYN[Dynamics]
    FM --> PIPE[Pipe Flow]
    FM --> OC[Open Channel Flow]
    FM --> MACH[Hydraulic Machines]

    PROP --> MANO[Manometry]
    PROP --> BUOY[Buoyancy & Flotation]

    KIN --> STREAM[Stream, Path, Streak lines]
    KIN --> CONT[Continuity Equation]

    DYN --> BER[Bernoulli's Equation]
    DYN --> MOM[Momentum Equation]

    PIPE --> LAM[Laminar & Turbulent]
    PIPE --> DW[Darcy-Weisbach]
    PIPE --> MOODY[Moody Chart]

    OC --> SE[Specific Energy]
    OC --> HJ[Hydraulic Jump]
    OC --> GVF[Gradually Varied Flow]

    MACH --> PUMP[Centrifugal Pumps]
    MACH --> TURB[Pelton, Francis, Kaplan]
</div>

<script type="module">
  import mermaid from "https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs";
  mermaid.initialize({ startOnLoad: true });
</script>

## 5. Water Resources Engineering
<div class="mermaid">
flowchart TD
    WR[Water Resources Engineering]
    WR --> HYD[Hydrology]
    WR --> IRR[Irrigation Engineering]

    HYD --> CYCLE[Hydrologic Cycle]
    HYD --> PRECIP[Precipitation & Evaporation]
    HYD --> INFIL[Infiltration & Runoff]
    HYD --> UH[Unit Hydrograph]
    HYD --> FLOOD[Flood Routing - Muskingum]
    HYD --> GW[Groundwater - Wells, Darcy]

    IRR --> DUTY[Duty, Delta, Base Period]
    IRR --> CANAL[Canal Design - Kennedy, Lacey]
    IRR --> DAM[Gravity Dams]
    IRR --> SEEP[Seepage Theories - Bligh, Khosla]
</div>

<script type="module">
  import mermaid from "https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs";
  mermaid.initialize({ startOnLoad: true });
</script>

## 6. Environmental Engineering
<div class="mermaid">
flowchart TD
    ENV[Environmental Engineering]
    ENV --> WTR[Water Treatment]
    ENV --> WW[Wastewater Treatment]
    ENV --> SWM[Solid Waste Management]
    ENV --> ANP[Air & Noise Pollution]

    WTR --> QUAL[BOD, COD, DO]
    WTR --> COAG[Coagulation & Flocculation]
    WTR --> SED[Sedimentation]
    WTR --> FILT[Filtration]
    WTR --> DISINF[Disinfection]

    WW --> SEW[Characteristics of Sewage]
    WW --> ASP[Activated Sludge Process]
    WW --> TF[Trickling Filters]

    SWM --> COLL[Collection & Transport]
    SWM --> DISP[Disposal Methods]

    ANP --> PLUME[Plume Rise]
    ANP --> CONTROL[Control Devices]
  </div>

<script type="module">
  import mermaid from "https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs";
  mermaid.initialize({ startOnLoad: true });
</script>

## 7. Transportation Engineering
<div class="mermaid">
flowchart TD
    TE[Transportation Engineering]
    TE --> HW[Highway Engineering]
    TE --> TRAF[Traffic Engineering]
    TE --> PAVE[Pavement Design]
    TE --> RWY[Railway Engineering]
    TE --> APT[Airport Engineering]

    HW --> GEO[Geometric Design - SSD, Curves]
    HW --> BIT[Bitumen Tests & Specifications]

    TRAF --> PARAM[Speed, Volume, Density]
    TRAF --> WEB[Webster's Signal Design]

    PAVE --> FLEX[Flexible - CBR, IRC-37]
    PAVE --> RIGID[Rigid - Westergaard]

    RWY --> GRAD[Gradients & Curves]
    RWY --> TURN[Turnout & Cant]

    APT --> ORIENT[Runway Orientation]
    APT --> LEN[Basic Runway Length]
  </div>

<script type="module">
  import mermaid from "https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs";
  mermaid.initialize({ startOnLoad: true });
</script>

## 8. Surveying
<div class="mermaid">
flowchart TD
    SURV[Surveying]
    SURV --> BASIC[Basic Methods]
    SURV --> THEO[Theodolite & Traversing]
    SURV --> TACH[Tacheometry]
    SURV --> CURVE[Curves]
    SURV --> MODERN[Modern Methods]

    BASIC --> CHAIN[Chain & Compass]
    BASIC --> LEV[Levelling - Dumpy, Reciprocal]

    THEO --> GALE[Gale's Table]
    THEO --> ADJ[Traverse Adjustments]

    TACH --> CONST[Tacheometric Constants]
    TACH --> RED[Subtense & Tangential]

    CURVE --> SIMP[Simple Curves]
    CURVE --> COMP[Compound & Reverse]

    MODERN --> GPS[GPS & GIS]
    MODERN --> RS[Remote Sensing Basics]
  </div>

<script type="module">
  import mermaid from "https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs";
  mermaid.initialize({ startOnLoad: true });
</script>

## 9. Construction Materials & Management
<div class="mermaid">
flowchart TD
    CMM[Construction Materials & Management]
    CMM --> MAT[Materials]
    CMM --> MGMT[Construction Management]
    CMM --> EQUIP[Equipment & Economics]

    MAT --> CEM[Cement - Types & Tests]
    MAT --> CONC[Concrete - Mix Design, Admixtures]
    MAT --> BRICK[Bricks, Timber, Paints]

    MGMT --> CHART[Bar Chart & CPM]
    MGMT --> PERT[PERT & Floats]
    MGMT --> CRASH[Time-Cost Crashing]

    EQUIP --> MACH[Bulldozer, Crane, Batching Plant]
    EQUIP --> ECON[Project Economics, Cost Slope]
</div>

<script type="module">
  import mermaid from "https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs";
  mermaid.initialize({ startOnLoad: true });
</script>
