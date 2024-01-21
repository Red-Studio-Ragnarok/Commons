# Ragnarök Versioning Convention Version 1.0

The Ragnarök Versioning Convention is used for Red Studio projects, providing a simple and easy to follow scheme for versioning. Version numbers follow one of these formats:

- X.Y
- X.Y.Z

Each component (X, Y, Z) represents a level of change:

## Major Version (X)

"X" represents the major version. Changes in the major version signal significant shifts in the project such as a complete redesign, major architectural change, or a major feature release. It's primarily used to keep the minor version within a single-digit range for simplicity.

When a project is in its beta phase, the major version is set to "0". This allows for up to ten updates before the product is ready for a stable release.

In beta, the following versions have specific focuses:

- 0.8: Emphasizes internal changes and structural modifications.
- 0.9: Focuses on refining existing features and functionality.
- 1.0: Completes a comprehensive bug sweep to ensure all known bugs are addressed before the stable release.

Upon incrementing the major version, minor and hotfix versions reset to zero.

## Minor Version (Y)

"Y" is the minor version. This number can increment up to infinity. When the major version is increased by one this resets to zero.

## Hotfix Version (Z)

"Z" is the hotfix version. These are expedient updates designed to address bugs and other pressing issues. Unlike minor versions, hotfix versions don't have an upper limit.

## Development (Dev) Versions

While working on an update, developers should append a "-Dev-X" suffix to the standard version number. Here, "X" is a number indicating the build's version. This number should be incremented each time a new build is published to provide a clear record of the development process.

## Compatibility

In beta phases, backward compatibility may break multiple times. Otherwise, the Ragnarök Versioning Convention doesn't provide explicit information about backward compatibility.
