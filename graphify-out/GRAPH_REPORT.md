# Graph Report - /home/bedrock_agentcore/app/claude-mem  (2026-04-22)

## Corpus Check
- 368 files · ~823,356 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 2163 nodes · 5595 edges · 91 communities detected
- Extraction: 73% EXTRACTED · 27% INFERRED · 0% AMBIGUOUS · INFERRED: 1499 edges (avg confidence: 0.8)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]
- [[_COMMUNITY_Community 2|Community 2]]
- [[_COMMUNITY_Community 3|Community 3]]
- [[_COMMUNITY_Community 4|Community 4]]
- [[_COMMUNITY_Community 5|Community 5]]
- [[_COMMUNITY_Community 6|Community 6]]
- [[_COMMUNITY_Community 7|Community 7]]
- [[_COMMUNITY_Community 8|Community 8]]
- [[_COMMUNITY_Community 9|Community 9]]
- [[_COMMUNITY_Community 10|Community 10]]
- [[_COMMUNITY_Community 11|Community 11]]
- [[_COMMUNITY_Community 12|Community 12]]
- [[_COMMUNITY_Community 13|Community 13]]
- [[_COMMUNITY_Community 14|Community 14]]
- [[_COMMUNITY_Community 15|Community 15]]
- [[_COMMUNITY_Community 16|Community 16]]
- [[_COMMUNITY_Community 17|Community 17]]
- [[_COMMUNITY_Community 18|Community 18]]
- [[_COMMUNITY_Community 19|Community 19]]
- [[_COMMUNITY_Community 20|Community 20]]
- [[_COMMUNITY_Community 21|Community 21]]
- [[_COMMUNITY_Community 22|Community 22]]
- [[_COMMUNITY_Community 23|Community 23]]
- [[_COMMUNITY_Community 24|Community 24]]
- [[_COMMUNITY_Community 25|Community 25]]
- [[_COMMUNITY_Community 26|Community 26]]
- [[_COMMUNITY_Community 27|Community 27]]
- [[_COMMUNITY_Community 28|Community 28]]
- [[_COMMUNITY_Community 29|Community 29]]
- [[_COMMUNITY_Community 30|Community 30]]
- [[_COMMUNITY_Community 31|Community 31]]
- [[_COMMUNITY_Community 32|Community 32]]
- [[_COMMUNITY_Community 33|Community 33]]
- [[_COMMUNITY_Community 34|Community 34]]
- [[_COMMUNITY_Community 35|Community 35]]
- [[_COMMUNITY_Community 36|Community 36]]
- [[_COMMUNITY_Community 37|Community 37]]
- [[_COMMUNITY_Community 38|Community 38]]
- [[_COMMUNITY_Community 39|Community 39]]
- [[_COMMUNITY_Community 40|Community 40]]
- [[_COMMUNITY_Community 41|Community 41]]
- [[_COMMUNITY_Community 42|Community 42]]
- [[_COMMUNITY_Community 43|Community 43]]
- [[_COMMUNITY_Community 44|Community 44]]
- [[_COMMUNITY_Community 45|Community 45]]
- [[_COMMUNITY_Community 46|Community 46]]
- [[_COMMUNITY_Community 47|Community 47]]
- [[_COMMUNITY_Community 48|Community 48]]
- [[_COMMUNITY_Community 49|Community 49]]
- [[_COMMUNITY_Community 50|Community 50]]
- [[_COMMUNITY_Community 51|Community 51]]
- [[_COMMUNITY_Community 52|Community 52]]
- [[_COMMUNITY_Community 53|Community 53]]
- [[_COMMUNITY_Community 54|Community 54]]
- [[_COMMUNITY_Community 55|Community 55]]
- [[_COMMUNITY_Community 56|Community 56]]
- [[_COMMUNITY_Community 57|Community 57]]
- [[_COMMUNITY_Community 58|Community 58]]
- [[_COMMUNITY_Community 59|Community 59]]
- [[_COMMUNITY_Community 60|Community 60]]
- [[_COMMUNITY_Community 61|Community 61]]
- [[_COMMUNITY_Community 62|Community 62]]
- [[_COMMUNITY_Community 63|Community 63]]
- [[_COMMUNITY_Community 64|Community 64]]
- [[_COMMUNITY_Community 65|Community 65]]
- [[_COMMUNITY_Community 66|Community 66]]
- [[_COMMUNITY_Community 67|Community 67]]
- [[_COMMUNITY_Community 68|Community 68]]
- [[_COMMUNITY_Community 69|Community 69]]
- [[_COMMUNITY_Community 70|Community 70]]
- [[_COMMUNITY_Community 71|Community 71]]
- [[_COMMUNITY_Community 72|Community 72]]
- [[_COMMUNITY_Community 73|Community 73]]
- [[_COMMUNITY_Community 74|Community 74]]
- [[_COMMUNITY_Community 75|Community 75]]
- [[_COMMUNITY_Community 76|Community 76]]
- [[_COMMUNITY_Community 77|Community 77]]
- [[_COMMUNITY_Community 78|Community 78]]
- [[_COMMUNITY_Community 79|Community 79]]
- [[_COMMUNITY_Community 80|Community 80]]
- [[_COMMUNITY_Community 81|Community 81]]
- [[_COMMUNITY_Community 82|Community 82]]
- [[_COMMUNITY_Community 83|Community 83]]
- [[_COMMUNITY_Community 84|Community 84]]
- [[_COMMUNITY_Community 85|Community 85]]
- [[_COMMUNITY_Community 86|Community 86]]
- [[_COMMUNITY_Community 87|Community 87]]
- [[_COMMUNITY_Community 88|Community 88]]
- [[_COMMUNITY_Community 89|Community 89]]
- [[_COMMUNITY_Community 90|Community 90]]

## God Nodes (most connected - your core abstractions)
1. `SessionStore` - 61 edges
2. `T()` - 49 edges
3. `kh()` - 42 edges
4. `PendingMessageStore` - 26 edges
5. `us()` - 24 edges
6. `Ie()` - 24 edges
7. `main()` - 24 edges
8. `op()` - 23 edges
9. `Logger` - 20 edges
10. `MigrationRunner` - 20 edges

## Surprising Connections (you probably didn't know these)
- `ClaudeMemPlugin()` --calls--> `On()`  [INFERRED]
  /home/bedrock_agentcore/app/claude-mem/src/integrations/opencode-plugin/index.ts → /home/bedrock_agentcore/app/claude-mem/plugin/ui/viewer-bundle.js
- `R()` --calls--> `tt()`  [INFERRED]
  /home/bedrock_agentcore/app/claude-mem/plugin/scripts/worker-cli.js → /home/bedrock_agentcore/app/claude-mem/plugin/ui/viewer-bundle.js
- `start()` --calls--> `$()`  [INFERRED]
  /home/bedrock_agentcore/app/claude-mem/plugin/scripts/worker-cli.js → /home/bedrock_agentcore/app/claude-mem/plugin/ui/viewer-bundle.js
- `startWithBun()` --calls--> `At()`  [INFERRED]
  /home/bedrock_agentcore/app/claude-mem/plugin/scripts/worker-cli.js → /home/bedrock_agentcore/app/claude-mem/plugin/ui/viewer-bundle.js
- `status()` --calls--> `badRequest()`  [INFERRED]
  /home/bedrock_agentcore/app/claude-mem/plugin/scripts/worker-cli.js → /home/bedrock_agentcore/app/claude-mem/src/services/worker/http/BaseRouteHandler.ts

## Communities

### Community 0 - "Community 0"
Cohesion: 0.02
Nodes (314): $(), $a(), Aa(), Ad(), Af(), Ag(), Al(), Am() (+306 more)

### Community 1 - "Community 1"
Cohesion: 0.02
Nodes (29): badRequest(), parseIntParam(), validateRequired(), CorpusRoutes, createSDKSession(), resolveCreateSessionArgs(), updateMemorySessionId(), createSessionWithMemoryId() (+21 more)

### Community 2 - "Community 2"
Cohesion: 0.02
Nodes (66): execGit(), execNpm(), getBranchInfo(), isValidBranchName(), pullUpdates(), switchBranch(), ChromaMcpManager, ChromaSync (+58 more)

### Community 3 - "Community 3"
Cohesion: 0.02
Nodes (47): importObservation(), importSdkSession(), importSessionSummary(), importUserPrompt(), getBunPath(), getBunPathOrThrow(), isBunAvailable(), CorpusStore (+39 more)

### Community 4 - "Community 4"
Cohesion: 0.03
Nodes (115): basicSession(), main(), multiTurn(), oneShot(), sessionResume(), analyzeTransformations(), discoverAgentFiles(), loadOriginalContent() (+107 more)

### Community 5 - "Community 5"
Cohesion: 0.04
Nodes (40): buildViewer(), ChromaSearchStrategy, estimateTokens(), extractRelevantFile(), findObservationsByFolder(), formatObservationsForClaudeMd(), generateClaudeMd(), getTrackedFolders() (+32 more)

### Community 6 - "Community 6"
Cohesion: 0.03
Nodes (65): cleanClaudeMd(), cleanNotes(), getReleaseNotes(), loadEnv(), main(), postToDiscord(), truncate(), exportMemories() (+57 more)

### Community 7 - "Community 7"
Cohesion: 0.05
Nodes (56): compactTime(), formatHeaderDateTime(), renderAgentColumnKey(), renderAgentContextEconomics(), renderAgentContextIndex(), renderAgentDayHeader(), renderAgentEmptyState(), renderAgentFooter() (+48 more)

### Community 8 - "Community 8"
Cohesion: 0.05
Nodes (28): runHealthCheck(), startHealthChecker(), stopHealthChecker(), configureSupervisorSignalHandlers(), getOrCreateContentSessionId(), startSupervisor(), stopSupervisor(), Supervisor (+20 more)

### Community 9 - "Community 9"
Cohesion: 0.08
Nodes (53): bunCandidatePaths(), getBunVersionString(), resolveBunBinaryPath(), detectInstalledIDEs(), getDetectedIDEs(), hasVscodeExtension(), isCommandInPath(), main() (+45 more)

### Community 10 - "Community 10"
Cohesion: 0.07
Nodes (48): handleError(), notFound(), AppError, createErrorResponse(), errorHandler(), notFoundHandler(), requireLocalhost(), dataIn() (+40 more)

### Community 11 - "Community 11"
Cohesion: 0.07
Nodes (32): assertSslFlag(), callTool(), connect(), getValueByPath(), isEmptyValue(), matchesRule(), parsePath(), resolveFields() (+24 more)

### Community 12 - "Community 12"
Cohesion: 0.06
Nodes (9): FormattingService, MemoryRoutes, createMiddleware(), ModeManager, getPackageCommandsDir(), getPackageRoot(), Server, SettingsRoutes (+1 more)

### Community 13 - "Community 13"
Cohesion: 0.08
Nodes (17): extractConversationTurns(), formatTranscriptToMarkdown(), formatTurnToMarkdown(), countTags(), stripMemoryTagsFromJson(), stripMemoryTagsFromPrompt(), stripTagsInternal(), formatPercentage() (+9 more)

### Community 14 - "Community 14"
Cohesion: 0.1
Nodes (35): main(), parseArgs(), printHelp(), printLanguages(), promptMultiline(), promptUser(), checkWorkerHealth(), collectDiagnostics() (+27 more)

### Community 15 - "Community 15"
Cohesion: 0.14
Nodes (29): buildSymbols(), detectLanguageWithUserGrammars(), extractSignatureFromLines(), findCommentAbove(), findContainingHeadingLevel(), findPythonDocstringFromLines(), formatFoldedView(), formatMarkdownFoldedView() (+21 more)

### Community 16 - "Community 16"
Cohesion: 0.11
Nodes (23): cleanReleaseBody(), exec(), extractVersion(), formatDate(), generateChangelog(), getReleases(), main(), buildTimestampMap() (+15 more)

### Community 17 - "Community 17"
Cohesion: 0.12
Nodes (24): writeAgentsMd(), formatTimelineForClaudeMd(), getTargetFilename(), hasConsecutiveDuplicateSegments(), isExcludedFolder(), isExcludedUnsafeDirectory(), isProjectRoot(), isValidPathForClaudeMd() (+16 more)

### Community 18 - "Community 18"
Cohesion: 0.11
Nodes (10): getArgValue(), runTranscriptCommand(), expandHomePath(), loadTranscriptWatchConfig(), writeSampleConfig(), closeHttpServer(), performGracefulShutdown(), loadWatchState() (+2 more)

### Community 19 - "Community 19"
Cohesion: 0.18
Nodes (17): componentDidCatch(), checkBinaryPlatformCompatibility(), compareVersions(), getBunPath(), getBunVersion(), getUvPath(), getUvVersion(), installBun() (+9 more)

### Community 20 - "Community 20"
Cohesion: 0.33
Nodes (15): checkOpenClawStatus(), findPluginManifestPath(), findPluginSkillsDirectory(), findPreBuiltPluginDirectory(), getOpenClawClaudeMemExtensionDirectory(), getOpenClawConfigDirectory(), getOpenClawConfigFilePath(), getOpenClawExtensionsDirectory() (+7 more)

### Community 21 - "Community 21"
Cohesion: 0.14
Nodes (10): App(), usePagination(), usePaginationFor(), useSettings(), useSSE(), useStats(), getStoredPreference(), getSystemTheme() (+2 more)

### Community 22 - "Community 22"
Cohesion: 0.22
Nodes (8): configureCursorMcp(), jsonGet(), parseArrayField(), readCursorRegistry(), registerCursorProject(), removeMcpConfig(), unregisterCursorProject(), writeCursorRegistry()

### Community 23 - "Community 23"
Cohesion: 0.22
Nodes (1): SearchOrchestrator

### Community 24 - "Community 24"
Cohesion: 0.36
Nodes (1): TimelineService

### Community 25 - "Community 25"
Cohesion: 0.54
Nodes (7): main(), normalizeAuthorName(), normalizeRepositoryUrl(), readJson(), syncClaudePlugin(), syncCodexPlugin(), writeJson()

### Community 26 - "Community 26"
Cohesion: 0.47
Nodes (3): analyzeFile(), isHighPriority(), isUIFile()

### Community 27 - "Community 27"
Cohesion: 0.33
Nodes (0): 

### Community 28 - "Community 28"
Cohesion: 0.33
Nodes (3): formatStarCount(), GitHubStarsButton(), useGitHubStars()

### Community 29 - "Community 29"
Cohesion: 0.4
Nodes (0): 

### Community 30 - "Community 30"
Cohesion: 0.5
Nodes (2): analyzeTryCatchBlock(), detectAntiPatterns()

### Community 31 - "Community 31"
Cohesion: 0.4
Nodes (0): 

### Community 32 - "Community 32"
Cohesion: 0.4
Nodes (0): 

### Community 33 - "Community 33"
Cohesion: 0.5
Nodes (0): 

### Community 34 - "Community 34"
Cohesion: 0.5
Nodes (0): 

### Community 35 - "Community 35"
Cohesion: 0.67
Nodes (2): isPortInUse(), waitForHealth()

### Community 36 - "Community 36"
Cohesion: 0.5
Nodes (0): 

### Community 37 - "Community 37"
Cohesion: 0.67
Nodes (0): 

### Community 38 - "Community 38"
Cohesion: 0.67
Nodes (0): 

### Community 39 - "Community 39"
Cohesion: 0.67
Nodes (0): 

### Community 40 - "Community 40"
Cohesion: 0.67
Nodes (0): 

### Community 41 - "Community 41"
Cohesion: 1.0
Nodes (0): 

### Community 42 - "Community 42"
Cohesion: 1.0
Nodes (0): 

### Community 43 - "Community 43"
Cohesion: 1.0
Nodes (0): 

### Community 44 - "Community 44"
Cohesion: 1.0
Nodes (0): 

### Community 45 - "Community 45"
Cohesion: 1.0
Nodes (0): 

### Community 46 - "Community 46"
Cohesion: 1.0
Nodes (0): 

### Community 47 - "Community 47"
Cohesion: 1.0
Nodes (0): 

### Community 48 - "Community 48"
Cohesion: 1.0
Nodes (0): 

### Community 49 - "Community 49"
Cohesion: 1.0
Nodes (0): 

### Community 50 - "Community 50"
Cohesion: 1.0
Nodes (0): 

### Community 51 - "Community 51"
Cohesion: 1.0
Nodes (0): 

### Community 52 - "Community 52"
Cohesion: 1.0
Nodes (0): 

### Community 53 - "Community 53"
Cohesion: 1.0
Nodes (0): 

### Community 54 - "Community 54"
Cohesion: 1.0
Nodes (0): 

### Community 55 - "Community 55"
Cohesion: 1.0
Nodes (0): 

### Community 56 - "Community 56"
Cohesion: 1.0
Nodes (0): 

### Community 57 - "Community 57"
Cohesion: 1.0
Nodes (0): 

### Community 58 - "Community 58"
Cohesion: 1.0
Nodes (0): 

### Community 59 - "Community 59"
Cohesion: 1.0
Nodes (0): 

### Community 60 - "Community 60"
Cohesion: 1.0
Nodes (0): 

### Community 61 - "Community 61"
Cohesion: 1.0
Nodes (0): 

### Community 62 - "Community 62"
Cohesion: 1.0
Nodes (0): 

### Community 63 - "Community 63"
Cohesion: 1.0
Nodes (0): 

### Community 64 - "Community 64"
Cohesion: 1.0
Nodes (0): 

### Community 65 - "Community 65"
Cohesion: 1.0
Nodes (0): 

### Community 66 - "Community 66"
Cohesion: 1.0
Nodes (0): 

### Community 67 - "Community 67"
Cohesion: 1.0
Nodes (0): 

### Community 68 - "Community 68"
Cohesion: 1.0
Nodes (0): 

### Community 69 - "Community 69"
Cohesion: 1.0
Nodes (0): 

### Community 70 - "Community 70"
Cohesion: 1.0
Nodes (0): 

### Community 71 - "Community 71"
Cohesion: 1.0
Nodes (0): 

### Community 72 - "Community 72"
Cohesion: 1.0
Nodes (0): 

### Community 73 - "Community 73"
Cohesion: 1.0
Nodes (0): 

### Community 74 - "Community 74"
Cohesion: 1.0
Nodes (0): 

### Community 75 - "Community 75"
Cohesion: 1.0
Nodes (0): 

### Community 76 - "Community 76"
Cohesion: 1.0
Nodes (0): 

### Community 77 - "Community 77"
Cohesion: 1.0
Nodes (0): 

### Community 78 - "Community 78"
Cohesion: 1.0
Nodes (0): 

### Community 79 - "Community 79"
Cohesion: 1.0
Nodes (0): 

### Community 80 - "Community 80"
Cohesion: 1.0
Nodes (0): 

### Community 81 - "Community 81"
Cohesion: 1.0
Nodes (0): 

### Community 82 - "Community 82"
Cohesion: 1.0
Nodes (0): 

### Community 83 - "Community 83"
Cohesion: 1.0
Nodes (0): 

### Community 84 - "Community 84"
Cohesion: 1.0
Nodes (0): 

### Community 85 - "Community 85"
Cohesion: 1.0
Nodes (0): 

### Community 86 - "Community 86"
Cohesion: 1.0
Nodes (0): 

### Community 87 - "Community 87"
Cohesion: 1.0
Nodes (0): 

### Community 88 - "Community 88"
Cohesion: 1.0
Nodes (0): 

### Community 89 - "Community 89"
Cohesion: 1.0
Nodes (0): 

### Community 90 - "Community 90"
Cohesion: 1.0
Nodes (0): 

## Knowledge Gaps
- **5 isolated node(s):** `Extract complete XML blocks from text`, `Check if XML block is an example/template`, `Process a single transcript file and extract only real XML from assistant respon`, `Extract complete XML blocks from text`, `Process a single transcript file and extract XML with timestamps`
  These have ≤1 connection - possible missing edges or undocumented components.
- **Thin community `Community 41`** (2 nodes): `sdk-agent-resume.test.ts`, `shouldPassResumeParameter()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 42`** (2 nodes): `hook-lifecycle.test.ts`, `fmt()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 43`** (2 nodes): `logger-format-tool.test.ts`, `formatTool()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 44`** (2 nodes): `getWorkerRestartInstructions()`, `error-messages.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 45`** (2 nodes): `mergeAndDeduplicateByProject()`, `data.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 46`** (2 nodes): `useSpinningFavicon.ts`, `useSpinningFavicon()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 47`** (2 nodes): `handleEsc()`, `ContextSettingsModal.tsx`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 48`** (2 nodes): `ThemeToggle.tsx`, `ThemeToggle()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 49`** (2 nodes): `ScrollToTop.tsx`, `ScrollToTop()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 50`** (2 nodes): `ObservationCard.tsx`, `stripProjectRoot()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 51`** (1 nodes): `test-sse-consumer.js`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 52`** (1 nodes): `statusline-counts.js`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 53`** (1 nodes): `build-worker-binary.js`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 54`** (1 nodes): `cursor-hooks-json-utils.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 55`** (1 nodes): `cursor-registry.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 56`** (1 nodes): `cursor-context-update.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 57`** (1 nodes): `json-utils.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 58`** (1 nodes): `npx-search-query-param.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 59`** (1 nodes): `gemini_agent.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 60`** (1 nodes): `plugin-scripts-line-endings.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 61`** (1 nodes): `context-injection.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 62`** (1 nodes): `cursor-mcp-config.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 63`** (1 nodes): `install-non-tty.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 64`** (1 nodes): `bun-runner.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 65`** (1 nodes): `codex-workspace-context.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 66`** (1 nodes): `skill-docs-placement.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 67`** (1 nodes): `stale-abort-controller-guard.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 68`** (1 nodes): `worker-daemon-port-race.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 69`** (1 nodes): `chroma-mcp-manager-cwd.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 70`** (1 nodes): `plugin-distribution.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 71`** (1 nodes): `version-consistency.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 72`** (1 nodes): `mcp-tool-schemas.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 73`** (1 nodes): `index.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 74`** (1 nodes): `Context.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 75`** (1 nodes): `index.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 76`** (1 nodes): `index.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 77`** (1 nodes): `index.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 78`** (1 nodes): `index.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 79`** (1 nodes): `hook-response.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 80`** (1 nodes): `types.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 81`** (1 nodes): `index.tsx`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 82`** (1 nodes): `ui.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 83`** (1 nodes): `api.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 84`** (1 nodes): `timing.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 85`** (1 nodes): `settings.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 86`** (1 nodes): `TerminalPreview.tsx`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 87`** (1 nodes): `Feed.tsx`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 88`** (1 nodes): `SummaryCard.tsx`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 89`** (1 nodes): `tree-kill.d.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 90`** (1 nodes): `installer.js`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Logger` connect `Community 2` to `Community 0`, `Community 1`, `Community 3`, `Community 4`, `Community 6`?**
  _High betweenness centrality (0.044) - this node is a cross-community bridge._
- **Why does `SessionStore` connect `Community 3` to `Community 1`, `Community 2`, `Community 5`?**
  _High betweenness centrality (0.031) - this node is a cross-community bridge._
- **Why does `SearchOrchestrator` connect `Community 23` to `Community 1`, `Community 5`?**
  _High betweenness centrality (0.023) - this node is a cross-community bridge._
- **What connects `Extract complete XML blocks from text`, `Check if XML block is an example/template`, `Process a single transcript file and extract only real XML from assistant respon` to the rest of the system?**
  _5 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.02 - nodes in this community are weakly interconnected._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.02 - nodes in this community are weakly interconnected._
- **Should `Community 2` be split into smaller, more focused modules?**
  _Cohesion score 0.02 - nodes in this community are weakly interconnected._