##Circadian Phase Relationship Between CRT and General Activity Rhythms in DD

To determine the circadian phase relationship between CRT and general activity rhythms in DD, an onset on the first day of the 10-day quantification interval in DD described previously was detected as a phase marker by the following method:
At first, to increase the accuracy of the period calculation, five days before and after the 10-day interval were attached to the original interval. After a period with the 20-day data was estimated, the data were split in time by that period, summed, and normalized to max and min values.

The normalized one-circadian-cycle data were summed cumulatively further and detrended. Local peaks and troughs of the detrended data were detected. Among many candidates of troughs as an onset, a trough of the closest peak-trough pairs whose mutual distance is largest was defind as the first onset of 20-day data. Finally, the first onset of 10-day data was calculated using the first onset and period of the 20-day data. The analysis was performed using custom MATLAB scripts available at: https://github.com/Takahashi-Lab-UTSW/Actogram-onset-detection.

##Tb Average During Subjective Day and Subjective Night in DD
To determine Tb average during subjective day (SD) and subjective night (SN) in DD separately, Tb data within the identical 10-day data in DD described previously were divided into 2 segments (namely SD and SN datasets, respectively) according to the circadian phase of CRT (see Section Circadian phase relationship between CRT and general activity rhythms in DD for details). For arrhythmic mice, SD and SN data were separeted equally in time.

All data after the first artificial Tb onset were included in the analysis and divided into 10 SN and SD segments (tau/2), respectively, according to tau. A SN dataset includes all 10 SN segments isolated from the first halves (tau/2) of 10 circadian cycles across the 10 days, whereas data in the remaining second halves (tau/2) were grouped as a SD dataset.

The analysis was performed using the same custom MATLAB scripts as ones used for estimating periods previously. Two-way ANOVAs were performed with Prism to compare Tb average between SD and SN within each group, as well as SD or SN Tb average between control and experimental groups (Figure 1G, 2F, 3F, 4F, 5H).

