[![DOI](https://img.shields.io/badge/DOI-10.82901%2Fnemar.on003655-blue)](https://doi.org/10.82901/nemar.on003655)

raw EEG in a modified Sternberg working memory paradigm with two types of task: with mental manipulations (alphabetization) and simple retention (TASK) and 3 levels of load: 5, 6, or 7 letter to memorize (LOAD).

Events.tsv files in eeg folders contain event descriptions (see column trial_type). 

trial_type = {  
    '500' 'start of the trial';
    '150' 'start of the baseline period: Retention of 5 letters (5R)';
    '151' 'start of the baseline period: Manipulation with 5 letters (5M)';
    '160' 'start of the baseline period: Retention of 6 letters (6R)';
    '161' 'start of the baseline period: Manipulation with 6 letters (6M)';
    '170' 'start of the baseline period: Retention of 7 letters (7R)';
    '171' 'start of the baseline period: Manipulation with 7 letters (7M)';
    '4' 'presentation of the task instruction';
    '250' 'encoding: 5R';
    '251' 'encoding: 5M';
    '260' 'encoding: 6R';
    '261' 'encoding: 6M';
    '270' 'encoding: 7R';
    '271' 'encoding: 7M';
    '350' 'delay period: 5R';
    '351' 'delay period: 5M';
    '360' 'delay period: 6R';
    '361' 'delay period: 6M';
    '370' 'delay period: 7R';
    '371' 'delay period: 7M';
    '50' 'probe: 5R';
    '51' 'probe: 5M';
    '60' 'probe: 6R';
    '61' 'probe: 6M';
    '70' 'probe: 7R';
    '71' 'probe: 7M';
    '4500' 'Response: 5R: error';
    '4501' 'Response: 5R: correct';
    '4510' 'Response: 5M: error';
    '4511' 'Response: 5M: correct';
    '4600' 'Response: 6R: error';
    '4601' 'Response: 6R: correct';
    '4610' 'Response: 6M: error';
    '4611' 'Response: 6M: correct';
    '4700' 'Response: 7R: error';
    '4701' 'Response: 7R: correct';
    '4710' 'Response: 7M: error';
    '4711' 'Response: 7M: correct'
    };