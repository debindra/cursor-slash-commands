# Multi-Platform Development Workflow

Coordinate cross-platform development for web, mobile, and desktop applications.

## Usage
/multi-platform [feature description] [target platforms]

## Example
/multi-platform user authentication web, iOS, and Android

## Workflow Steps

1. **Platform Analysis Agent**
   - Identify target platforms
   - Analyze platform-specific requirements
   - Determine shared vs platform-specific code
   - Plan architecture for code sharing
   - Identify platform constraints

2. **Shared Code Agent**
   - Design shared business logic
   - Create common data models
   - Implement shared utilities
   - Design API contracts
   - Create shared types/interfaces

3. **Platform-Specific Agent**
   - Generate web implementation
   - Generate mobile (iOS/Android) implementation
   - Generate desktop implementation
   - Handle platform-specific UI/UX
   - Implement platform APIs

4. **Integration Agent**
   - Integrate shared and platform code
   - Handle platform-specific build configs
   - Set up cross-platform testing
   - Configure deployment pipelines
   - Create platform-specific documentation

5. **Testing Agent**
   - Generate cross-platform tests
   - Create platform-specific test suites
   - Set up E2E tests for each platform
   - Test platform integrations

## Output
- Shared codebase
- Platform-specific implementations
- Build configurations
- Test suites for each platform
- Deployment configurations
- Documentation

## Variables
$ARGUMENTS - Feature description and target platforms

## Supported Platforms
- Web (React, Vue, Angular, etc.)
- iOS (Swift, React Native, Flutter)
- Android (Kotlin, Java, React Native, Flutter)
- Desktop (Electron, Tauri, native)
- Cross-platform frameworks (React Native, Flutter, Xamarin)

## Architecture Patterns
- Shared business logic
- Platform-specific UI
- Code sharing strategies
- Native module integration

