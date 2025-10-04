# Changelog

## [0.11-exp] - 2025-10-02

### Added
* Support for updating Baked NavMesh at runtime
* Frustum culling for the nav mesh debug drawers
* Config var options to control alpha, draw distance etc for debug drawers
* Parallel debug drawer support
* Split out the NavMeshQueue so you can integrate NavMeshQuery requests with the existing queue system to balance workloads

### Changed
* Updated a lot of documentation on code
* NavMeshSurfaceAuthoring gizmo is now 5x+ faster

### Fixed
* Terrain baking at non 1:1 scales
* Potential system ordering issue with a new NavigationSystemGroup

## [0.10.0-exp] - 2025-08-17

### Added
* Compression to baking
* Compression to terrain

### Changed
* Rewrote Recast as HPC and removed native libraries

### Fixed
* Samples updated and some minor issues fixed

## [0.9.1-exp] - 2025-06-07

### Added
* General purpose WorldBounds component with quantization extensions.

### Changed
* Updated to core 1.4.3

### Fixed
* Unity Physics dependency
* A bunch of issues with the Sample

### Removed
* References to Unity.Logging

### Documentation
* Improved Samples documentation

## [0.9.0-exp] - 2025-05-18

### Added
* Initial release