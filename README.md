# Crime Video Dataset

**Documentation and Usage Instructions**

## Dataset Authors

| No. | Author | Email |
|---|---|---|
| 1 | Bommadi Hemanth Kumar Reddy | cb.sc.u4cse23113@cb.students.amrita.edu |
| 2 | Pattem Hemanth Kumar Reddy | cb.sc.u4cse23763@cb.students.amrita.edu |
| 3 | Nelluri Praveen | cb.sc.u4cse23131@cb.students.amrita.edu |
| 4 | Padmanabhuni Ankith | cb.sc.u4cse23133@cb.students.amrita.edu |
| 5 | Ramireddygari Yasaswini | cb.sc.u4cse23566@cb.students.amrita.edu |

**Department of Computer Science and Engineering**  
Amrita School of Computing, Amrita Vishwa Vidyapeetham, Coimbatore, India

---

## 1. Dataset Overview

This dataset supports research on fine-grained crime video classification and temporal action recognition. It contains video samples organized into 13 crime/action categories, with each video associated with a category label for supervised learning and evaluation.

**Total number of videos: 826 across 13 categories.**

The class-wise counts are listed below.

## 2. Dataset Categories and Video Counts

| No. | Class Label | Video Count |
|---|---|---|
| 1 | Abuse | 59 |
| 2 | Dragging | 69 |
| 3 | Hair Pulling | 54 |
| 4 | Hitting | 69 |
| 5 | Kicking | 61 |
| 6 | Neck Grabbing | 60 |
| 7 | Punching | 63 |
| 8 | Pushing | 71 |
| 9 | Robbery | 58 |
| 10 | Shooting | 64 |
| 11 | Slapping | 63 |
| 12 | Snatching | 61 |
| 13 | Stabbing | 74 |
| | **Total Videos** | **826** |

**Class-count note:** The counts range from 54 to 74 videos per class. Hair Pulling (54), Robbery (58), and Abuse (59) have fewer than 60 videos.

---

## 3. Recommended File Organization

Use this as a suggested structure and adjust it to match the actual uploaded files:

```text
CrimeVideoDataset/
├── videos/
│   ├── Abuse/
│   ├── Dragging/
│   ├── Hair_Pulling/
│   ├── Hitting/
│   ├── Kicking/
│   ├── Neck_Grabbing/
│   ├── Punching/
│   ├── Pushing/
│   ├── Robbery/
│   ├── Shooting/
│   ├── Slapping/
│   ├── Snatching/
│   └── Stabbing/
├── metadata.csv
├── train.csv (if included)
├── val.csv (if included)
└── README.txt
```

## 4. Metadata and Labels

If a metadata CSV is included, recommended fields are:

- **video_id:** Unique identifier
- **filename:** File path
- **class_label:** One of the 13 labels
- **split:** Optional train/validation/test label
- **duration_seconds:** Optional video duration

## 5. Instructions for Use

1. Download all archive files in the dataset release.
2. Extract each ZIP archive while preserving its folder structure.
3. Read the metadata file, if provided, and match filenames to class labels.
4. Use the labels to prepare a supervised video-classification dataset.
5. Follow provided train/validation/test split files, if included, for reproducible evaluation.
6. Check that every referenced video exists and can be decoded.

## 6. Research Applications

Potential applications include:

- Fine-grained crime video classification
- Temporal action recognition
- Video representation learning
- Feature extraction
- Comparative evaluation of deep-learning approaches for video understanding

## 7. Data Format and Archives

Video files may be distributed in ZIP archives.

If multiple ZIP files are used, document which classes or videos each archive contains.

Keep metadata and split files consistent with the released videos.

## 8. Data Quality Checks

Before publication, verify that:

- Videos can be decoded.
- Filenames and metadata paths are correct.
- Class labels are accurate.
- All referenced files are included.
- The actual count for every class and the final dataset total are reported.

## 9. Ethics, Privacy, and Redistribution

Before publication, confirm that you have permission to redistribute every video.

Review applicable consent, privacy, and legal requirements, and state any restrictions clearly in the dataset record and license.

## 10. Citation and Versioning

After publication, cite the official dataset title, author list, publication year, and DOI assigned by IEEE DataPort.

**Do not invent a DOI before it is issued.**

For future releases, assign a version number and summarize changes to videos, labels, metadata, or splits.
