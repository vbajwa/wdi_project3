USER STORIES HAND-JOB

As a user,

* I want to see a main page, with a list of my current patients in a sidebar.
* When I click on a patient, it fills the patient's info onto the page.
* When the patient info fills the page, it pushes other elements out dgoddamnway
* The patient info should include the following:
  Basic info:
    - :Name t.string
    - :MRN t.integer
    - :Attending Name t.string
    - :Room Number t.string
    - :Full Code Status t.boolean
    - :DOB t.string
    - :Age t.integer
    - :allergies/ drug allergies t.string
    - :diet t.string
    - :Next of Kin name t.string
    - :Phone Number t.string
    - :Needs_Isolation? t.boolean

  Situation and Background:
    - :CC t.string
    - :PMH t.string (diagnoses api)
    - :Surgical Hx t.(diagnoses api)
    - :family history t.string
    - :social history t.string
      - smoking
      - alcohol
      - drugs
      - psych hx
      - occupation


  Assessment:
    - Vital signs: O2 sat, RR, HR, BP, T
    - Labs: skeletons for cbc, bmp, lft and pt/ptt/inr and OTHER (cardiac enzymes (troponin trends), etc) with options to trend values.
        -- and other as a text string

    - Imaging: selections for CXR, CT, EKG, XRAY, MRI ETC and a brief message on what was found.

    - Other diagnostic procedures performed: biopsies, LP, stress tests, etc

    - current medications with dosage and route



    Objective by System: (all notes will include consults)
      :Neuro 
      LOC/Mental status (AAOx3), GCS (if icu)
        notes: pupils, reflexes, Activity, restraints, procedures
      :Cardiovascular:
        rhythm (NSR?)
        ejection fraction
        notes
      :Pulmonary:
        vent settings
        ABG trends
      :GI/ABD
        NPO?
        Diet?
        Tubes? (NG, OG, PEG)
        notes: (bms, sounds, etc)
      :GU/Renal
        foley: y/n, date placed
        notes:
      :Endocrine
        Glucose sticks trended
        notes:
      :ID
        SIRS/SEPSIS alerts?
        antibiotics
        cultures- sputum, blood 1/2, urine, nares, wound
      :Skin/MSK
        Intact Checkbox
        wound care
        incision
        decubitis ulcers?
        edema
        PT

Assess ment and Plan


* I can see pertinent information, and tehn expand to see that total information
* I can click something that takes me to a printable version, showing all patients and pertinent info in a table.
