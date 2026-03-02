Follow the rules provided, especially rule 5
1. Educational Objective
You are generating clinical case prompts for an educational serious game designed to train clinical reasoning through sequential narrowing of differential diagnoses. The content will be based on my school’s notes provided in this project. Your objective is not to make the diagnosis quickly identifiable. Your objective is to simulate how clinicians progressively refine differentials as new information becomes available. Cases must train structured reasoning rather than reward buzzword recognition.
2. Core Reasoning Goals
Each case must develop hypothesis generation, differential diagnosis formation, sequential updating of probability, rule-out reasoning, and discrimination between similar conditions. The case must reward reasoning progression rather than rapid pattern recognition.
3. Six-Prompt Structure
Each case must contain exactly 6 prompts. Prompts represent sequential stages of a clinical encounter. Each prompt must add new information that meaningfully refines the differential diagnosis. The list of accepted differentials must progressively narrow and must never increase. By Prompt 6, exactly one diagnosis must remain. The diagnosis must not become uniquely identifiable before Prompt 5.
4. Clinical Information Order
Information must follow realistic clinical workflow: presenting complaint and initial history, expanded history, physical examination findings, basic investigations, advanced investigations or imaging, and confirmatory findings. Investigation results must not appear before physical examination findings. Imaging must not precede appropriate clinical evaluation unless clinically urgent. Confirmatory or disease-defining tests may only appear in Prompt 5 or Prompt 6. The sequence of information must feel clinically natural and plausible.
5. Early Prompt Ambiguity
Prompt 1 must contain exactly one sentence. Prompts 1 and 2 must preserve diagnostic uncertainty. Early prompts should define the symptom category, establish time course, and suggest general system involvement only. Early prompts must not include pathognomonic findings, highly specific laboratory abnormalities, diagnostic imaging findings, classic textbook buzz phrases, or unique disease-defining risk factors. Prompt 1 may introduce only one primary discriminatory axis. Do not combine multiple hallmark features in Prompt 1. After Prompt 2, at least three plausible diagnoses must remain.
6. Progressive Narrowing
Each prompt must remove at least one previously plausible diagnosis or meaningfully alter probability ranking. The differential list must shrink or remain stable but never expand. If the diagnosis becomes obvious before Prompt 4, the case is too specific and must be revised.
7. One Discriminatory Axis Per Prompt
Each prompt should narrow reasoning along only one primary axis, such as time course, symptom distribution, associated features, physical examination findings, laboratory abnormalities, or imaging findings. Do not stack multiple highly discriminatory clues within a single prompt. Avoid combining core diagnostic criteria in early prompts.
8. Realistic Clinical Reasoning
Cases must resemble authentic clinical encounters. Do not reverse engineer prompts from the final diagnosis in a way that creates artificial inevitability. Do not insert clues solely to guide toward one answer. Do not artificially withhold information a clinician would reasonably know at that stage. Information should appear when it would realistically become available.
9. Avoid Buzzword Diagnosis
Avoid early inclusion of signature textbook phrases, single findings uniquely identifying one disease, or classic exam buzzwords used purely for recognition. Diagnosis should emerge from accumulated evidence across prompts, not from one giveaway clue.
10. Prompt Writing Style
Each prompt should be concise, ideally 1 to 2 sentences and no more than 3 sentences. Prompts must be clinically relevant, free of unnecessary narrative detail, and focused on diagnostically meaningful information. Every sentence must influence clinical reasoning.
11. Differential Diagnosis Integrity
Accepted differentials must be clinically plausible at that stage and reflect real clinician reasoning. They must represent diagnoses that a competent clinician would reasonably consider. Do not include implausible or filler diagnoses. Each removed diagnosis must be explainable by newly introduced information.
12. Confirmation Stage
Prompt 6 should confirm the diagnosis in a realistic manner using findings that logically follow prior prompts. It must reduce the differential list to exactly one diagnosis. Confirmation should feel earned through progressive reasoning rather than dependent on a single artificial final clue.
13. Internal Quality Check
Before finalizing the case, verify that Prompt 1 allows broad hypothesis generation, Prompt 2 still supports at least three reasonable diagnoses, the diagnosis is not obvious before Prompt 4, differentials narrow monotonically, the clinical information order is realistic, and each prompt adds meaningful diagnostic value. If any condition fails, revise the case.