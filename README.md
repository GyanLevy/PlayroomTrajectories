# PlayroomTrajectories

**Trajectory-Based Analysis of Repetitive Movement in Autistic and Typical Children**

Capstone project (Software Engineering, course 61998), 2026–2027.

## About

The project uses computer vision and unsupervised learning to identify and characterize
repetitive patterns in the movement trajectories of children with and without autism
in a playroom.

A fixed camera records each child during free play. We track the child, map the
track onto floor coordinates, and analyze the resulting trajectory (x, y, t) for
recurring paths and movement patterns.

This project continues [PlayroomHAR](https://github.com/VictorRyskinB/PlayroomHAR),
which built the video tracking pipeline (YOLOv8, ByteTrack, floor homography).
We build the analysis layer on top of the trajectories it produces.

## Team

- **Students:** Gyan Levy, Shira Segev.
- **Advisors:** Julia Sheidin, Anat Dahan.
- **Research collaborators:** clinical and developmental psychology researchers, University of Haifa

## Repository structure

```
book/           Project book (Phase A and Phase B)
presentation/   Presentation slides
docs/           Meeting notes, literature list, working documents
src/            Source code (Phase B)
```

## Data and privacy

The dataset consists of video recordings of children and is **not stored in this
repository**. Videos, extracted trajectories and any per-child results are kept
outside version control, and the `.gitignore` blocks common video and data formats.

Figures in the book and presentation show trajectory maps and heatmaps only, and
any frame taken from a video has the child's face blurred.

## Use of AI tools

During the preparation of this project we used Claude and ChatGPT. After using these
tools, we reviewed and edited the content as needed and take full responsibility for
the results. Links to the conversations are included in the project book.
