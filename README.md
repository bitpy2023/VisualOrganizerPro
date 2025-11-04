# VisualOrganizerPro
Visual Organizer Pro – Smart Image Management with AI &amp; GUI
# Project Structure – VisualOrganizerPro

> آخرین به‌روزرسانی: 2025-11-04

<details>
<summary>نمایش ساختار کامل پروژه</summary>

VisualOrganizerPro
├── backup_imports/
│   └── data/
│       └── cache/
│           └── models/
│               ├── models.py
│               └── settings/
│                   ├── recent_folders.json
│                   ├── window_state.json
│                   └── thumbnails/
│                       └── fix_learning.json
├── deployment/
│   └── build_scripts/
│       ├── build.py
│       └── logs/
│           ├── app.log
│           └── visual_organizer.log
├── pics/
│   └── jungle.jpg
├── src/
│   └── core/
│       └── database/
│           ├── feature_storage.py
│           ├── image_database.py
│           ├── metadata_manager.py
│           ├── models.py
│           ├── schema.py
│           └── init.py
│       └── search_engine/
│           ├── query_processor.py
│           ├── search_engine.py
│           ├── vector_index.py
│           └── similarity_search/
│               ├── faiss_engine.py
│               └── init.py
│       └── vision_engine/
│           ├── duplicates.py
│           ├── extractor.py
│           ├── feature_extractor.py
│           ├── image_analyzer.py
│           └── init.py
│       └── init.py
│   └── gui/
│       └── preview_panel/
│           ├── image_preview.py
│           ├── metadata_panel.py
│           ├── similarity_view.py
│           └── init.py
│       └── search_panel/
│           ├── auto_search_engine.py
│           ├── results_grid.py
│           ├── search_panel.py
│           └── init.py
│       └── smart_gallery/
│           ├── album_manager.py
│           ├── gallery_view.py
│           ├── layout_manager.py
│           ├── thumbnail_cache.py
│           ├── thumbnail_widget.py
│           └── init.py
│       └── widgets/
│           ├── base_widget.py
│           ├── batch_actions.py
│           ├── category_sidebar.py
│           ├── image_quality_indicator.py
│           ├── search_suggestions.py
│           ├── smart_slider.py
│           ├── tag_cloud.py
│           └── init.py
│       ├── main_window.py
│       └── init.py
│   └── integration/
│       ├── app_controller.py
│       ├── background_processor.py
│       ├── cache_manager.py
│       ├── performance_optimizer.py
│       ├── utils.py
│       └── init.py
├── tests/
│   ├── test_extractor.py
│   ├── test_integration.py
│   ├── test_search.py
│   ├── test_vision_engine.py
│   └── utils/
│       ├── config_manager.py
│       ├── image_utils.py
│       ├── logger.py
│       └── fix_imports.py
├── install_requirements.py
├── main.py
├── PROJECT_STRUCTURE.ps1
├── README_TECHNICAL.md
├── requirements.txt
└── test_imports.py


</details>
