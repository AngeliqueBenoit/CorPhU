#--------------------------------------
# CorPhU
CORrection of Phase Unwrapping errors in SAR interferometry.

# Example of a command line to run the algorithm (see unwCorrector.py other input arguments)
python unwCorrector.py --filesDir IGRAMS --igramName filt_fine.unw --proc isce --proc_iterations 0 --h5file corrector.h5

# Outputs
Interferograms are copied with a "corrected" extension and corrected from unwrapping errors by the algorithm.
The number of pixels corrected, not corrected, iteration number and triplets are saved in a h5 file.
