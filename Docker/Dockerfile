FROM quay.io/refgenomics/docker-ubuntu:14.04

MAINTAINER James Hummer <james.b.hummer@gmail.com>

#first installed bwa for comparison
RUN apt-get update
RUN apt-get install bwa

#then installed samtools and bcftools for analysis
RUN apt-get install -y samtools
RUN apt-get install -y bcftools

#then installed pandas and matplotlib for visualization
RUN import pandas as pd
RUN import matplotlib.pyplot as plt
