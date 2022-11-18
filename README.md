# International collaboration on new data collections
Machine Learning for Health 2022
28 November, New Orleans
In-Person Roundtable 8:
How to incentivize creation or publication of new data collections and facilitate international collaboration?

## Introduction
Global collaboration to collect and share large medical datasets is the key to improve clinical impact of machine learning (ML) in healthcare domain.
However, barriers such as privacy concerns and data bias still remain. 
In this roundtable, we aim to discuss the challenges and suggestions to incentivize creation or publication of new data collections and facilitate international collaboration

## 1. Background
The rapid increase in the adoption of electronic health records (EHRs) for recording patients’ data across different healthcare systems worldwide, 
along with the swift pace of applying ML methods to study various problems in this domain has led to a surge of ML tools that work on top of EHRs. 
Despite the great potential and huge interest, 
there remain noticeable barriers in front of both technical and biomedical communities to create impactful and reliable ML tools 
that can meaningfully improve individuals’ health.
Among the primary barriers is having access to large EHR datasets. 
However, due to issues of patient privacy and interoperability among digital systems, 
it is traditionally difficult to acquire and process EHR data for the research community at large scale. 
The Medical Information Mart for Intensive Care (MIMIC) dataset series [6] is the first open-access, freely available, large single-source EHR database that alleviates this difficulty, among other major openly available EHR datasets, 
including eICU [8], HiRID [2, 12], All of Us [5, 4], and the synthetic repositories like Synthea [10].

## 2. Problems
Protection of patient privacy is an important ethical consideration prior to data collection and sharing. 
In United States, the Health Insurance Portability and Accountability Act (HIPAA) protects sensitive patient information and levies stiff penalties on clinical organizations for non-compliance. 
European Union adopted a new Regulation 2016/679 on the protection of personal data. 
The European Patients’ Forum has actively advocated for a balanced approach to protect patients’ privacy while ensuring patient’s data can be shared
for healthcare and research purposes since the publication of the proposal for a regulation in 2012. 
If organizations and communities can enact responsible data sharing frameworks that follow international privacy rules, cross-institutional data sharing can become a norm [3].
Even if all the data were accessible, there would still be some difficulties to train machine learning models on all shared data considering that medical datasets are usually heterogeneous and enormous in size. 
Thus, it is necessary to develop unbiased training algorithms [3] and portable machine learning frameworks such as federated learning [11, 7].

## 3. Suggestions
1. Share the models instead of the original sensitive data using mimic learning approaches [1] 
and develop novel algorithms to train models to overcome data bias [3].
2. Encourage responsible data sharing to mitigate the effects of sample bias and develop
more generalizable machine learning models for real world deployment [3].

## Discussion Questions (3-5 questions)
1. Could you share your experience in incentivizing creation or publication of new data collections and facilitating international collaboration?
2. What are the main challenges in current data collections and international collaboration?
3. Do you have any suggestions to incentivize creation or publication of new data collections and facilitate international collaboration?

## Summary (100-200 words)
(Please fill in after the symposium, feel free to add references such as [9])

## References
[1] Mohamed Baza et al. “On sharing models instead of data using mimic learning for
smart health applications”. In: 2020 IEEE International Conference on Informatics,
IoT, and Enabling Technologies (ICIoT). IEEE. 2020, pp. 231–236.
[2] M. Faltys et al. “HiRID, A High Time-Resolution ICU Dataset (version 1.1.1)”. In:
(2021).
[3] Bilwaj Gaonkar, K Kim, and Luke Macyszyn. “Ethical issues arising due to bias in
training AI algorithms in healthcare and data sharing as a potential solution”. In: AI
Ethics J 1.1 (2020), pp. 1–9.
[4] Mehak Gupta et al. “Flexible-Window Predictions on Electronic Health Records”.
In: Proceedings of the AAAI Conference on Artificial Intelligence 36.11 (June 2022),
pp. 12510–12516. doi: 10.1609/aaai.v36i11.21520. url: https://ojs.aaai.org/
index.php/AAAI/article/view/21520.
[5] All of Us Research Program Investigators. “The “All of Us” research program”. In:
New England Journal of Medicine 381.7 (2019), pp. 668–676. issn: 0028-4793.
[6] A. Johnson et al. “MIMIC-IV (version 1.0)”. In: (2021). url: https://doi.org/10.
13026/s6n6-xd98.
[7] Brendan McMahan et al. “Communication-efficient learning of deep networks from
decentralized data”. In: Artificial intelligence and statistics. PMLR. 2017, pp. 1273–
1282.
[8] Tom J Pollard et al. “The eICU Collaborative Research Database, a freely available
multi-center database for critical care research”. In: Scientific data 5.1 (2018), pp. 1–
13.
[9] Subhrajit Roy et al. “Machine Learning for Health (ML4H) 2021”. In: Machine Learning for Health. PMLR. 2021, pp. 1–12.
[10] Jason Walonoski et al. “Synthea: An approach, method, and software mechanism for
generating synthetic patients and the synthetic electronic health care record”. In:
Journal of the American Medical Informatics Association 25.3 (Aug. 2017), pp. 230–
238. issn: 1527-974X.
[11] Qiang Yang et al. “Federated machine learning: Concept and applications”. In: ACM
Transactions on Intelligent Systems and Technology (TIST) 10.2 (2019), pp. 1–19.
[12] Hugo Y`eche et al. “HiRID-ICU-Benchmark–A Comprehensive Machine Learning Benchmark on High-resolution ICU Data”. In: arXiv preprint arXiv:2111.08536 (2021).
