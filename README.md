# TikTok-Dataset-Hypothesis-testing

# TikTok Video Metrics Analysis

## Dataset Overview

The dataset contains metrics for TikTok videos and user status information. The key columns in the dataset are:

- **claim_status**: TikTok assigned number for video with claim/opinion.
- **video_id**: Random identifying number assigned to video upon publication on TikTok.
- **video_duration_sec**: Duration of the video in seconds.
- **video_transcription_text**: Transcribed text of the words spoken in the video.
- **verified_status**: Indicates if the TikTok user is "verified" or "not verified".
- **author_ban_status**: Status of the TikTok user in terms of permissions: "active," "under review," or "banned".
- **video_view_count**: Total number of views the video has received.
- **video_like_count**: Total number of likes the video has received.
- **video_share_count**: Total number of times the video has been shared.
- **video_download_count**: Total number of times the video has been downloaded.
- **video_comment_count**: Total number of comments on the video.

## Project Goals

This project aims to analyze TikTok video metrics to determine how different factors impact video performance. Specifically, we focus on:

1. **Impact of User Verification Status**:
   - Compare the average number of video views between verified and non-verified users.
   - Hypotheses:
     - **H0**: The mean number of video views is the same for verified and non-verified users.
     - **H1**: The mean number of video views is different between verified and non-verified users.

2. **Impact of Author Ban Status**:
   - Examine how the author ban status (active, under review, or banned) affects video metrics, including likes, views, shares, and comments.
   - Hypotheses:
     - **H0**: There is no significant difference in the average number of video metrics (likes, views, shares, comments) among different author ban status groups.
     - **H1**: There is a significant difference in the average number of video metrics among different author ban status groups.

## Statistical Methods

- **T-Test**: Used to compare the means of two groups (e.g., verified vs. non-verified users) to determine if there is a statistically significant difference in video metrics.
- **Z-Test**: An alternative method to test for differences in means, particularly useful for larger sample sizes.
- **ANOVA**: Used to compare the means across multiple groups (e.g., different author ban statuses) to determine if there are significant differences in video metrics.

## Results

- **T-Test Results**: Provided insights into the statistical significance of differences in video metrics between two groups.
- **Z-Test Results**: Offered an alternative perspective on the significance of the differences.
- **ANOVA Results**: Allowed comparison of means across multiple groups to identify significant variations in video metrics.

## Conclusion

The analysis aims to provide actionable insights into how TikTok user verification and ban statuses affect video performance, helping to understand the impact of these factors on user engagement.

For detailed code and results, refer to the [Jupyter Notebooks](./notebooks) and [scripts](./scripts) directories.

