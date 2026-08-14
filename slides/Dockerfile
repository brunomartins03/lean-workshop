FROM texlive/texlive:latest-small

RUN tlmgr install \
    csquotes  \
    biblatex  \
    biber     \
    booktabs  \
    paratype  \
    etoolbox  \
    logreq    \
    && rm -rf /tmp/*
