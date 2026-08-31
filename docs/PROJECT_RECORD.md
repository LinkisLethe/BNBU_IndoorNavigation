# Project record / 项目记录

Updated: 2026-08-31 / 更新日期：2026-08-31

## English

This Android indoor-navigation course project provides route planning and real-time, continuous tracking. Motion-based dead reckoning alone caused the estimated path to drift over time. Wi-Fi measurements were introduced to correct the drift, and the update logic was refined through repeated testing to reject unreliable readings. The reported mean localization error decreased from approximately 2.4 m to 1.5 m, with more stable continuous tracking.

The repository does not include the raw localization measurements underlying this comparison. The result describes the course project; it is not a general indoor-positioning benchmark.

## 中文

这项 Android 室内导航课程项目实现了路径规划和实时连续跟踪。仅依赖运动信息进行航位推算时，估计路径会随时间漂移。项目引入 Wi-Fi 测量校正漂移，并通过反复测试调整更新逻辑，排除不可靠读数。记录的平均定位误差由约 2.4 m 降至 1.5 m，连续跟踪也更稳定。

仓库未包含这一误差对比的原始定位测量记录。这是课程项目的结果，不应视为通用室内定位基准。
