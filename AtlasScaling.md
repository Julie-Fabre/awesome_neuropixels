The 3D insertiong-planning tools (Neuropixels Trajectory Explorer, Pinpoint and HERBS) use a (scaled) version of the Allen Atlas, and they disagree with other standard atlases like Franklin & Paxinos. This is because the Allen CCF atlas is not the size of the average mouse brain, and the tilt of the atlas is not leveled at bregma and lambda.

To correct for these:
- scaling has been approximated based on this MRI data: https://www.nature.com/articles/s41467-018-04921-2
- tilt values have been approximated based on empiral estimated from the IBL: https://www.biorxiv.org/content/10.1101/2022.05.09.491042v6 (figure 2f). The tilt for cerebrum regions still disagrees significantly with the Franklin & Paxinos Atlas, by around an additional 5*:

<img src="./images/tilt.svg" width="100%">
