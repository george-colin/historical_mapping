# historical_mapping
Work related to historical mapping, in particular creating GIS maps from scans of old paper maps of Japan, using neural nets.

What the directories are:


50000_ROUND1:                       political boundaries from 50000 scale maps, now deprecated because we have better results  
50000_ROUND2:                       political boundaries from 50000 scale maps, better quality, but not (quite) the best results  
50000_ROUND2_renamed_to_numbers:    identical to 50000_ROUND2, but the map ids are different (i.e. a different map naming scheme was used)  

50000_ROUND2_size32_nnet:                     political boundaries from 50000 scale maps, best quality results - **USE THIS**  
50000_ROUND2_size32_nnet_renamed_to_numbers:  identical to 50000_ROUND2_size32_nnet, but the map ids are different (i.e. a different map naming scheme was used) - **OR USE THIS**  

ROUND1_maps:    political boundaries from 20000 and 25000 scale maps, now deprecated because we have better results  
ROUND2_maps:    political boundaries from 20000 and 25000 scale maps, best quality results - **USE THIS**  
