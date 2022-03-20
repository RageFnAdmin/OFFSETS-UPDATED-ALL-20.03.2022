open it as a raw



{"version":"++Fortnite+Release-19.40-CL-19215531-Windows"

  UWorld 0xB973AA8
  UObject 0xB79F1C8
  Free 0xB5F050
  WorldToScreen 0x7B6B81C
  GetNameByIndex 0xB91890
  BoneArray 0x4C0
  GetBoneWithRotation 0x1C0
  CameraX 0x7E8
  CameraY 0x12C
  Zoom 0x580

  GameInstance
  GameInstance::LocalPlayers 0x38
  GameInstance::OnlineSession 0x48
  GameInstance::ReferencedObjects 0x50
  GameInstance::OnPawnControllerChangedDelegates 0x78

  ActorComponent
  ActorComponent::PrimaryComponentTick 0x30
  ActorComponent::ComponentTags 0x60
  ActorComponent::AssetUserData 0x70
  ActorComponent::UCSSerializationIndex 0x84
  ActorComponent::bNetAddressable 0x88
  ActorComponent::bReplicates 0x88
  ActorComponent::bAutoActivate 0x89
  ActorComponent::bIsActive 0x8A
  ActorComponent::bEditableWhenInherited 0x8A
  ActorComponent::bCanEverAffectNavigation 0x8A
  ActorComponent::bIsEditorOnly 0x8A
  ActorComponent::CreationMethod 0x8C
  ActorComponent::OnComponentActivated 0x8D
  ActorComponent::OnComponentDeactivated 0x8E
  ActorComponent::UCSModifiedProperties 0x90

  Actor
  constexpr auto PrimaryActorTick = 0x28; // FActorTickFunction
			constexpr auto bCallPreReplication = 0x58; // char : 1
			constexpr auto bHidden = 0x58; // char : 1
			constexpr auto bCallPreReplicationForReplay = 0x58; // char : 1
			constexpr auto bNetTemporary = 0x58; // char : 1
			constexpr auto bReplicateMovement = 0x58; // char : 1
			constexpr auto bAlwaysRelevant = 0x58; // char : 1
			constexpr auto bOnlyRelevantToOwner = 0x58; // char : 1
			constexpr auto bNetStartup = 0x58; // char : 1
			constexpr auto bTearOff = 0x59; // char : 1
			constexpr auto bExchangedRoles = 0x59; // char : 1
			constexpr auto bNetLoadOnClient = 0x59; // char : 1
			constexpr auto bNetUseOwnerRelevancy = 0x59; // char : 1
			constexpr auto bRelevantForNetworkReplays = 0x59; // char : 1
			constexpr auto bRelevantForLevelBounds = 0x59; // char : 1
			constexpr auto bReplayRewindable = 0x59; // char : 1
			constexpr auto bForceNetAddressable = 0x59; // char : 1
			constexpr auto bFindCameraComponentWhenViewTarget = 0x5a; // char : 1
			constexpr auto bIgnoresOriginShifting = 0x5a; // char : 1
			constexpr auto bGenerateOverlapEventsDuringLevelStreaming = 0x5a; // char : 1
			constexpr auto bCanBeDamaged = 0x5a; // char : 1
			constexpr auto bCollideWhenPlacing = 0x5a; // char : 1
			constexpr auto bAutoDestroyWhenFinished = 0x5a; // char : 1
			constexpr auto bAllowTickBeforeBeginPlay = 0x5a; // char : 1
			constexpr auto bBlockInput = 0x5a; // char : 1
			constexpr auto bCanBeInCluster = 0x5b; // char : 1
			constexpr auto bReplicateUsingRegisteredSubObjectList = 0x5b; // char : 1
			constexpr auto bAllowReceiveTickEventOnDedicatedServer = 0x5b; // char : 1
			constexpr auto bReplicates = 0x5b; // char : 1
			constexpr auto bActorSeamlessTraveled = 0x5b; // char : 1
			constexpr auto bIsEditorOnlyActor = 0x5b; // char : 1
			constexpr auto bEnableAutoLODGeneration = 0x5b; // char : 1
			constexpr auto bActorEnableCollision = 0x5c; // char : 1
			constexpr auto bActorIsBeingDestroyed = 0x5c; // char : 1
			constexpr auto UpdateOverlapsMethodDuringLevelStreaming = 0x5e; // EActorUpdateOverlapsMethod
			constexpr auto DefaultUpdateOverlapsMethodDuringLevelStreaming = 0x5f; // EActorUpdateOverlapsMethod
			constexpr auto RemoteRole = 0x60; // ENetRole
			constexpr auto ReplicatedMovement = 0x68; // FRepMovement
			constexpr auto InitialLifeSpan = 0xd0; // float
			constexpr auto CustomTimeDilation = 0xd4; // float
			constexpr auto AttachmentReplication = 0xe0; // FRepAttachment
			constexpr auto Owner = 0x140; // AActor*
			constexpr auto NetDriverName = 0x148; // FName
			constexpr auto Role = 0x14c; // ENetRole
			constexpr auto NetDormancy = 0x14d; // ENetDormancy
			constexpr auto SpawnCollisionHandlingMethod = 0x14e; // ESpawnActorCollisionHandlingMethod
			constexpr auto AutoReceiveInput = 0x14f; // EAutoReceiveInput
			constexpr auto InputPriority = 0x150; // int32_t
			constexpr auto InputComponent = 0x158; // UInputComponent*
			constexpr auto NetCullDistanceSquared = 0x160; // float
			constexpr auto NetTag = 0x164; // int32_t
			constexpr auto NetUpdateFrequency = 0x168; // float
			constexpr auto MinNetUpdateFrequency = 0x16c; // float
			constexpr auto NetPriority = 0x170; // float
			constexpr auto Instigator = 0x178; // APawn*
			constexpr auto Children = 0x180; // TArray<AActor*>
			constexpr auto RootComponent = 0x190; // USceneComponent*
			constexpr auto RayTracingGroupId = 0x1a0; // int32_t
			constexpr auto Layers = 0x1a8; // TArray<FName>
			constexpr auto ParentComponent = 0x1b8; // TWeakObjectPtr<UChildActorComponent>
			constexpr auto Tags = 0x1c8; // TArray<FName>
			constexpr auto OnTakeAnyDamage = 0x1d8; // FMulticastSparseDelegate
			constexpr auto OnTakePointDamage = 0x1d9; // FMulticastSparseDelegate
			constexpr auto OnTakeRadialDamage = 0x1da; // FMulticastSparseDelegate
			constexpr auto OnActorBeginOverlap = 0x1db; // FMulticastSparseDelegate
			constexpr auto OnActorEndOverlap = 0x1dc; // FMulticastSparseDelegate
			constexpr auto OnBeginCursorOver = 0x1dd; // FMulticastSparseDelegate
			constexpr auto OnEndCursorOver = 0x1de; // FMulticastSparseDelegate
			constexpr auto OnClicked = 0x1df; // FMulticastSparseDelegate
			constexpr auto OnReleased = 0x1e0; // FMulticastSparseDelegate
			constexpr auto OnInputTouchBegin = 0x1e1; // FMulticastSparseDelegate
			constexpr auto OnInputTouchEnd = 0x1e2; // FMulticastSparseDelegate
			constexpr auto OnInputTouchEnter = 0x1e3; // FMulticastSparseDelegate
			constexpr auto OnInputTouchLeave = 0x1e4; // FMulticastSparseDelegate
			constexpr auto OnActorHit = 0x1e5; // FMulticastSparseDelegate
			constexpr auto OnDestroyed = 0x1e6; // FMulticastSparseDelegate
			constexpr auto OnEndPlay = 0x1e7; // FMulticastSparseDelegate
			constexpr auto InstanceComponents = 0x268; // TArray<UActorComponent*>
			constexpr auto BlueprintCreatedComponents = 0x278; // TArray<UActorComponent*>

  SceneComponent
  constexpr auto PhysicsVolume = 0xb8; // TWeakObjectPtr<APhysicsVolume>
  constexpr auto AttachParent = 0xc0; // USceneComponent*
  constexpr auto AttachSocketName = 0xc8; // FName
  constexpr auto AttachChildren = 0xd0; // TArray<USceneComponent*>
  constexpr auto ClientAttachedChildren = 0xe0; // TArray<USceneComponent*>
  constexpr auto RelativeLocation = 0x138; // FVector
  constexpr auto RelativeRotation = 0x150; // FRotator
  constexpr auto RelativeScale3D = 0x168; // FVector
  constexpr auto ComponentVelocity = 0x180; // FVector
			constexpr auto bShouldSnapLocationWhenAttached = 0x198; // char : 1
			constexpr auto bShouldBeAttached = 0x198; // char : 1
			constexpr auto bVisible = 0x198; // char : 1
			constexpr auto bAbsoluteScale = 0x198; // char : 1
			constexpr auto bAbsoluteRotation = 0x198; // char : 1
			constexpr auto bAbsoluteLocation = 0x198; // char : 1
			constexpr auto bComponentToWorldUpdated = 0x198; // char : 1
			constexpr auto bShouldSnapRotationWhenAttached = 0x199; // char : 1
			constexpr auto bShouldUpdatePhysicsVolume = 0x199; // char : 1
			constexpr auto bHiddenInGame = 0x199; // char : 1
			constexpr auto bBoundsChangeTriggersStreamingDataRebuild = 0x199; // char : 1
			constexpr auto bUseAttachParentBound = 0x199; // char : 1
			constexpr auto bComputeFastLocalBounds = 0x199; // char : 1
			constexpr auto bComputeBoundsOnceForGame = 0x199; // char : 1
			constexpr auto bComputedBoundsOnceForGame = 0x199; // char : 1
			constexpr auto Mobility = 0x19b; // EComponentMobility
			constexpr auto DetailMode = 0x19c; // EDetailMode
			constexpr auto PhysicsVolumeChangedDelegate = 0x19d; // FMulticastSparseDelegate

  Pawn
constexpr auto bUseControllerRotationPitch = 0x2a0; // char : 1
			constexpr auto bUseControllerRotationYaw = 0x2a0; // char : 1
			constexpr auto bUseControllerRotationRoll = 0x2a0; // char : 1
			constexpr auto bCanAffectNavigationGeneration = 0x2a0; // char : 1
			constexpr auto bIsLocalViewTarget = 0x2a0; // char : 1
			constexpr auto BaseEyeHeight = 0x2a4; // float
			constexpr auto AutoPossessPlayer = 0x2a8; // EAutoReceiveInput
			constexpr auto AutoPossessAI = 0x2a9; // EAutoPossessAI
			constexpr auto RemoteViewPitch = 0x2aa; // char
			constexpr auto AIControllerClass = 0x2b0; // AController*
			constexpr auto PlayerState = 0x2b8; // APlayerState*
			constexpr auto LastHitBy = 0x2c8; // AController*
			constexpr auto Controller = 0x2d0; // AController*
			constexpr auto PreviousController = 0x2d8; // AController*
			constexpr auto ReceiveControllerChangedDelegate = 0x2e4; // FMulticastSparseDelegate
			constexpr auto ReceiveRestartedDelegate = 0x2e5; // FMulticastSparseDelegate
			constexpr auto ControlInputVector = 0x2e8; // FVector
			constexpr auto LastControlInputVector = 0x300; // FVector

  DefaultPawn
  DefaultPawn::BaseTurnRate 0x288
  DefaultPawn::BaseLookUpRate 0x28C
  DefaultPawn::MovementComponent 0x290
  DefaultPawn::CollisionComponent 0x298
  DefaultPawn::MeshComponent 0x2A0
  DefaultPawn::bAddDefaultMovementBindings 0x2A8

  SkinnedMeshComponent
  SkinnedMeshComponent::SkeletalMesh 0x490
  SkinnedMeshComponent::MasterPoseComponent 0x498
  SkinnedMeshComponent::SkinCacheUsage 0x4A0
  SkinnedMeshComponent::VertexOffsetUsage 0x4B0
  SkinnedMeshComponent::PhysicsAssetOverride 0x5B8
  SkinnedMeshComponent::ForcedLodModel 0x5C0
  SkinnedMeshComponent::MinLodModel 0x5C4
  SkinnedMeshComponent::StreamingDistanceMultiplier 0x5D0
  SkinnedMeshComponent::LODInfo 0x5E0
  SkinnedMeshComponent::VisibilityBasedAnimTickOption 0x614
  SkinnedMeshComponent::bOverrideMinLOD 0x616
  SkinnedMeshComponent::bUseBoundsFromMasterPoseComponent 0x616
  SkinnedMeshComponent::bForceWireframe 0x616
  SkinnedMeshComponent::bDisplayBones 0x616
  SkinnedMeshComponent::bDisableMorphTarget 0x616
  SkinnedMeshComponent::bHideSkin 0x617
  SkinnedMeshComponent::bPerBoneMotionBlur 0x617
  SkinnedMeshComponent::bComponentUseFixedSkelBounds 0x617
  SkinnedMeshComponent::bConsiderAllBodiesForBounds 0x617
  SkinnedMeshComponent::bSyncAttachParentLOD 0x617
  SkinnedMeshComponent::bCanHighlightSelectedSections 0x617
  SkinnedMeshComponent::bRecentlyRendered 0x617
  SkinnedMeshComponent::bCastCapsuleDirectShadow 0x617
  SkinnedMeshComponent::bCastCapsuleIndirectShadow 0x618
  SkinnedMeshComponent::bCPUSkinning 0x618
  SkinnedMeshComponent::bEnableUpdateRateOptimizations 0x618
  SkinnedMeshComponent::bDisplayDebugUpdateRateOptimizations 0x618
  SkinnedMeshComponent::bRenderStatic 0x618
  SkinnedMeshComponent::bIgnoreMasterPoseComponentLOD 0x618
  SkinnedMeshComponent::bCachedLocalBoundsUpToDate 0x619
  SkinnedMeshComponent::bForceMeshObjectUpdate 0x619
  SkinnedMeshComponent::CapsuleIndirectShadowMinVisibility 0x61C
  SkinnedMeshComponent::CachedWorldSpaceBounds 0x648
  SkinnedMeshComponent::CachedWorldToLocalTransform 0x670

  SkeletalMeshComponent
 constexpr auto AnimBlueprintGeneratedClass = 0x820; // ClassPtrProperty
			constexpr auto AnimClass = 0x828; // UAnimInstance*
			constexpr auto AnimScriptInstance = 0x830; // UAnimInstance*
			constexpr auto PostProcessAnimInstance = 0x838; // UAnimInstance*
			constexpr auto AnimationData = 0x840; // FSingleAnimationPlayData
			constexpr auto RootBoneTranslation = 0x868; // FVector
			constexpr auto LineCheckBoundsScale = 0x880; // FVector
			constexpr auto LinkedInstances = 0x8c8; // TArray<UAnimInstance*>
			constexpr auto CachedBoneSpaceTransforms = 0x8d8; // TArray<FTransform>
			constexpr auto CachedComponentSpaceTransforms = 0x8e8; // TArray<FTransform>
			constexpr auto GlobalAnimRateScale = 0x9a8; // float
			constexpr auto KinematicBonesUpdateType = 0x9ac; // EKinematicBonesUpdateToPhysics
			constexpr auto PhysicsTransformUpdateMode = 0x9ad; // EPhysicsTransformUpdateMode
			constexpr auto AnimationMode = 0x9af; // EAnimationMode
			constexpr auto bEnablePhysicsOnDedicatedServer = 0x9b1; // char : 1
			constexpr auto bUpdateJointsFromAnimation = 0x9b1; // char : 1
			constexpr auto bUpdateOverlapsOnAnimationFinalize = 0x9b1; // char : 1
			constexpr auto bBlendPhysics = 0x9b1; // char : 1
			constexpr auto bHasValidBodies = 0x9b1; // char : 1
			constexpr auto bDisablePostProcessBlueprint = 0x9b1; // char : 1
			constexpr auto bAllowClothActors = 0x9b2; // char : 1
			constexpr auto bDisableClothSimulation = 0x9b2; // char : 1
			constexpr auto bDisableRigidBodyAnimNode = 0x9b8; // char : 1
			constexpr auto bAllowAnimCurveEvaluation = 0x9b8; // char : 1
			constexpr auto bDisableAnimCurves = 0x9b8; // char : 1
			constexpr auto bCollideWithEnvironment = 0x9b8; // char : 1
			constexpr auto bCollideWithAttachedChildren = 0x9b8; // char : 1
			constexpr auto bEnablePerPolyCollision = 0x9b9; // char : 1
			constexpr auto bUseRefPoseOnInitAnim = 0x9b9; // char : 1
			constexpr auto bPauseAnims = 0x9b9; // char : 1
			constexpr auto bNoSkeletonUpdate = 0x9b9; // char : 1
			constexpr auto bDeferKinematicBoneUpdate = 0x9b9; // char : 1
			constexpr auto bLocalSpaceSimulation = 0x9b9; // char : 1
			constexpr auto bResetAfterTeleport = 0x9b9; // char : 1
			constexpr auto bForceRefpose = 0x9ba; // char : 1
			constexpr auto bOnlyAllowAutonomousTickPose = 0x9ba; // char : 1
			constexpr auto bIsAutonomousTickPose = 0x9ba; // char : 1
			constexpr auto bOldForceRefPose = 0x9ba; // char : 1
			constexpr auto bShowPrePhysBones = 0x9ba; // char : 1
			constexpr auto bRequiredBonesUpToDate = 0x9ba; // char : 1
			constexpr auto bAnimTreeInitialised = 0x9ba; // char : 1
			constexpr auto bIncludeComponentLocationIntoBounds = 0x9ba; // char : 1
			constexpr auto bSkipBoundsUpdateWhenInterpolating = 0x9bb; // char : 1
			constexpr auto bNeedsQueuedAnimEventsDispatched = 0x9bb; // char : 1
			constexpr auto bSkipKinematicUpdateWhenInterpolating = 0x9bb; // char : 1
			constexpr auto bPropagateCurvesToSlaves = 0x9bb; // char : 1
			constexpr auto bEnableLineCheckWithBounds = 0x9bb; // char : 1
			constexpr auto CachedAnimCurveUidVersion = 0x9bc; // uint16_t
			constexpr auto ClothBlendWeight = 0x9c0; // float
			constexpr auto bWaitForParallelClothTask = 0x9c4; // bool
			constexpr auto DisallowedAnimCurves = 0x9c8; // TArray<FName>
			constexpr auto BodySetup = 0x9d8; // UBodySetup*
			constexpr auto ClothMaxDistanceScale = 0x9e4; // float
			constexpr auto OnConstraintBroken = 0x9e8; // FMulticastInlineDelegate
			constexpr auto OnPlasticDeformation = 0x9f8; // FMulticastInlineDelegate
			constexpr auto ClothingSimulationFactory = 0xa08; // UClothingSimulationFactory*
			constexpr auto TeleportDistanceThreshold = 0xb08; // float
			constexpr auto TeleportRotationThreshold = 0xb0c; // float
			constexpr auto LastPoseTickFrame = 0xb18; // uint32_t
			constexpr auto ClothingInteractor = 0xbb0; // UClothingSimulationInteractor*
			constexpr auto OnAnimInitialized = 0xc80; // FMulticastInlineDelegate

  AnimInstance
  AnimInstance::CurrentSkeleton 0x28
  AnimInstance::RootMotionMode 0x30
  AnimInstance::bUseMultiThreadedAnimationUpdate 0x31
  AnimInstance::bUsingCopyPoseFromMesh 0x31
  AnimInstance::bReceiveNotifiesFromLinkedInstances 0x31
  AnimInstance::bPropagateNotifiesToLinkedInstances 0x31
  AnimInstance::bUseMainInstanceMontageEvaluationData 0x31
  AnimInstance::bQueueMontageEvents 0x31
  AnimInstance::OnMontageBlendingOut 0x38
  AnimInstance::OnMontageStarted 0x48
  AnimInstance::OnMontageEnded 0x58
  AnimInstance::OnAllMontageInstancesEnded 0x68
  AnimInstance::NotifyQueue 0x150
  AnimInstance::ActiveAnimNotifyState 0x1C0
  AnimInstance::ActiveAnimNotifyEventReference 0x1D0

  Controller
  Controller::PlayerState 0x228
  Controller::OnInstigatedAnyDamage 0x238
  Controller::OnPossessedPawnChanged 0x248
  Controller::StateName 0x258
  Controller::Pawn 0x260
  Controller::Character 0x270
  Controller::TransformComponent 0x278
  Controller::ControlRotation 0x298
  Controller::bAttachToPawn 0x2A4

  PlayerController
  constexpr auto Player = 0x330; // UPlayer*
			constexpr auto AcknowledgedPawn = 0x338; // APawn*
			constexpr auto ControllingDirTrackInst = 0x340; // UInterpTrackInstDirector*
			constexpr auto MyHUD = 0x348; // AHUD*
			constexpr auto PlayerCameraManager = 0x350; // APlayerCameraManager*
			constexpr auto PlayerCameraManagerClass = 0x358; // APlayerCameraManager*
			constexpr auto bAutoManageActiveCameraTarget = 0x360; // bool
			constexpr auto TargetViewRotation = 0x368; // FRotator
			constexpr auto SmoothTargetViewRotationSpeed = 0x398; // float
			constexpr auto HiddenActors = 0x3a0; // TArray<AActor*>
			constexpr auto HiddenPrimitiveComponents = 0x3b0; // TArray<TWeakObjectPtr<UPrimitiveComponent>>
			constexpr auto LastSpectatorStateSynchTime = 0x3c4; // float
			constexpr auto LastSpectatorSyncLocation = 0x3c8; // FVector
			constexpr auto LastSpectatorSyncRotation = 0x3e0; // FRotator
			constexpr auto ClientCap = 0x3f8; // int32_t
			constexpr auto CheatManager = 0x400; // UCheatManager*
			constexpr auto CheatClass = 0x408; // UCheatManager*
			constexpr auto PlayerInput = 0x410; // UPlayerInput*
			constexpr auto ActiveForceFeedbackEffects = 0x418; // TArray<FActiveForceFeedbackEffect>
			constexpr auto bPlayerIsWaiting = 0x4a8; // char : 1
			constexpr auto NetPlayerIndex = 0x4ac; // char
			constexpr auto PendingSwapConnection = 0x508; // UNetConnection*
			constexpr auto NetConnection = 0x510; // UNetConnection*
			constexpr auto InputYawScale = 0x530; // float
			constexpr auto InputPitchScale = 0x534; // float
			constexpr auto InputRollScale = 0x538; // float
			constexpr auto bShowMouseCursor = 0x53c; // char : 1
			constexpr auto bEnableClickEvents = 0x53c; // char : 1
			constexpr auto bEnableTouchEvents = 0x53c; // char : 1
			constexpr auto bEnableMouseOverEvents = 0x53c; // char : 1
			constexpr auto bEnableTouchOverEvents = 0x53c; // char : 1
			constexpr auto bForceFeedbackEnabled = 0x53c; // char : 1
			constexpr auto bEnableStreamingSource = 0x53c; // char : 1
			constexpr auto bStreamingSourceShouldActivate = 0x53c; // char : 1
			constexpr auto ForceFeedbackScale = 0x540; // float
			constexpr auto ClickEventKeys = 0x548; // TArray<FKey>
			constexpr auto DefaultMouseCursor = 0x558; // EMouseCursor
			constexpr auto CurrentMouseCursor = 0x559; // EMouseCursor
			constexpr auto DefaultClickTraceChannel = 0x55a; // ECollisionChannel
			constexpr auto CurrentClickTraceChannel = 0x55b; // ECollisionChannel
			constexpr auto HitResultTraceDistance = 0x55c; // float
			constexpr auto SeamlessTravelCount = 0x560; // uint16_t
			constexpr auto LastCompletedSeamlessTravelCount = 0x562; // uint16_t
			constexpr auto InactiveStateInputComponent = 0x5d8; // UInputComponent*
			constexpr auto bShouldPerformFullTickWhenPaused = 0x5e0; // char : 1
			constexpr auto CurrentTouchInterface = 0x5f8; // UTouchInterface*
			constexpr auto SpectatorPawn = 0x678; // ASpectatorPawn*
			constexpr auto bIsLocalPlayerController = 0x684; // bool
			constexpr auto SpawnLocation = 0x688; // FVector

namespace APlayerCameraManager
		{
			constexpr auto PCOwner = 0x298; // APlayerController*
			constexpr auto TransformComponent = 0x2a0; // USceneComponent*
			constexpr auto DefaultFOV = 0x2ac; // float
			constexpr auto DefaultOrthoWidth = 0x2b4; // float
			constexpr auto DefaultAspectRatio = 0x2bc; // float
			constexpr auto CameraCache = 0x330; // FCameraCacheEntry
			constexpr auto LastFrameCameraCache = 0xab0; // FCameraCacheEntry
			constexpr auto ViewTarget = 0x1230; // FTViewTarget
			constexpr auto PendingViewTarget = 0x19c0; // FTViewTarget
			constexpr auto CameraCachePrivate = 0x2180; // FCameraCacheEntry
			constexpr auto LastFrameCameraCachePrivate = 0x2900; // FCameraCacheEntry
			constexpr auto ModifierList = 0x3080; // TArray<UCameraModifier*>
			constexpr auto DefaultModifiers = 0x3090; // TArray<UCameraModifier*>
			constexpr auto FreeCamDistance = 0x30a0; // float
			constexpr auto FreeCamOffset = 0x30a8; // FVector
			constexpr auto ViewTargetOffset = 0x30c0; // FVector
			constexpr auto OnAudioFadeChangeEvent = 0x30d8; // FMulticastInlineDelegate
			constexpr auto CameraLensEffects = 0x3100; // TArray<TScriptInterface<ICameraLensEffectInterface>>
			constexpr auto CachedCameraShakeMod = 0x3110; // UCameraModifier_CameraShake*
			constexpr auto AnimInstPool0x8 = 0x3118; // UCameraAnimInst*
			constexpr auto PostProcessBlendCache = 0x3158; // TArray<FPostProcessSettings>
			constexpr auto ActiveAnims = 0x3178; // TArray<UCameraAnimInst*>
			constexpr auto FreeAnims = 0x3188; // TArray<UCameraAnimInst*>
			constexpr auto AnimCameraActor = 0x3198; // ACameraActor*
			constexpr auto bClientSimulatingViewTarget = 0x31a0; // char : 1
			constexpr auto bUseClientSideCameraUpdates = 0x31a0; // char : 1
			constexpr auto bDefaultConstrainAspectRatio = 0x31a0; // char : 1
			constexpr auto bIsOrthographic = 0x31a0; // char : 1
			constexpr auto bGameCameraCutThisFrame = 0x31a1; // char : 1
			constexpr auto ViewPitchMin = 0x31a4; // float
			constexpr auto ViewPitchMax = 0x31a8; // float
			constexpr auto ViewYawMin = 0x31ac; // float
			constexpr auto ViewYawMax = 0x31b0; // float
			constexpr auto ViewRollMin = 0x31b4; // float
			constexpr auto ViewRollMax = 0x31b8; // float
			constexpr auto ServerUpdateCameraTimeout = 0x31c0; // float

  FortPlayerController
  FortPlayerController::OnPlayerPawnPossessed 0x728
  FortPlayerController::OnPickupCreated 0x738
  FortPlayerController::OnViewTargetChanged 0x778
  FortPlayerController::OnInputFiltered 0x788
  FortPlayerController::bAllowPcbBenefits 0x7A4
  FortPlayerController::OnFortPawnChangedEvent 0x7A8
  FortPlayerController::OnControllerComponentAttachedEvent 0x7B8
  FortPlayerController::bInPossession 0x861
  FortPlayerController::AircraftInputComponent 0x8B0
  FortPlayerController::MiniMapInputComponent 0x8B8
  FortPlayerController::SkydiveMusicAudioComp 0x8C0
  FortPlayerController::bFailedToRespawn 0x8C8
  FortPlayerController::bIsDisconnecting 0x8C8
  FortPlayerController::bIsBeingKicked 0x8C8
  FortPlayerController::bHasInitiallySpawned 0x8C8
  FortPlayerController::bAssignedStartSpawn 0x8C8
  FortPlayerController::bReadyToStartMatch 0x8C8
  FortPlayerController::bClientPawnIsLoaded 0x8C8
  FortPlayerController::SpawnLoc 0x8CC
  FortPlayerController::NumPreviousSpawns 0x8D8
  FortPlayerController::bCanSpectateBot 0x8DC
  FortPlayerController::OnBlueprintReadyCheckCompleted 0x8E0
  FortPlayerController::OnDelayForPreServerTransitionAnimationEvent 0x900
  FortPlayerController::SimpleLoadingScreenSoundMix 0x928
  FortPlayerController::RegisteredPartnerId 0x940
  FortPlayerController::RegisteredPartnerTag 0x950
  FortPlayerController::ManagedAIs 0x958
  FortPlayerController::MyFortPawn 0x968
  FortPlayerController::MyFortPawnBeforeTakeoverOfScriptedPawn 0x970
  FortPlayerController::ScriptedPawnControllerBeforeTakeover 0x978
  FortPlayerController::bHasClientFinishedLoading 0x980
  FortPlayerController::bHasServerFinishedLoading 0x981
  FortPlayerController::TimeStartedWaiting 0x984
  FortPlayerController::TimeFinishedNavigationBuild 0x988
  FortPlayerController::MaterialParameterCollection 0x990
  FortPlayerController::bLoadingScreenDropped 0x9A1
  FortPlayerController::PendingSpectatorLocation 0x9A4
  FortPlayerController::ActorUnderReticle 0x9B0
  FortPlayerController::AutoFireReticleTarget 0x9B8
  FortPlayerController::AutofireTimerHandle 0x9C0
  FortPlayerController::WeakspotUnderReticle 0x9D0
  FortPlayerController::ActiveWeakSpots 0x9D8
  FortPlayerController::IdleKickLastTimeActive 0x9E8
  FortPlayerController::LastTimeActive 0x9EC
  FortPlayerController::bRevertPlayerListenerChange 0xA10
  FortPlayerController::VehicleInputComponent 0xA30
  FortPlayerController::bHoldingPrimaryFireFromTouch 0xA38
  FortPlayerController::bSupportNextPieceAssist 0xA39
  FortPlayerController::bAutoBuildForTrapPlacement 0xA3A
  FortPlayerController::bAutoBuildForFloorTrapPlacement 0xA3B
  FortPlayerController::bAutoBuildForWallTrapPlacement 0xA3C
  FortPlayerController::bAutoBuildForCeilingTrapPlacement 0xA3D
  FortPlayerController::bNoControllerLighting 0xA3E
  FortPlayerController::ReturnToMainMenuTimeoutDelay 0xA40
  FortPlayerController::OnQuestObjectiveStateChanged 0xA48
  FortPlayerController::LastDamager 0xA70
  FortPlayerController::LastFallInstigator 0xA80
  FortPlayerController::LastDamagerCreditThresholdDropElim 0xA8C
  FortPlayerController::LastDamagerCreditThresholdSelfElim 0xA90
  FortPlayerController::LastDamagerCreditThresholdStormElim 0xA94
  FortPlayerController::bGiveLastDamagerElimCreditOnDrop 0xA98
  FortPlayerController::bGiveLastDamagerElimCreditOnSelfDamage 0xA99
  FortPlayerController::bGiveLastDamagerElimCreditOnStormDamage 0xA9A
  FortPlayerController::OnMcpProfilesInitializedEvent 0xAE8
  FortPlayerController::OnEnterVehicleDriver 0xC88
  FortPlayerController::OnEnterVehiclePassenger 0xC98
  FortPlayerController::OnExitVehicle 0xCA8
  FortPlayerController::OnFullyExitVehicle 0xCB8
  FortPlayerController::OnVehicleAbilitiesRemoved 0xCC8
  FortPlayerController::OnTetherChanged 0xCD8
  FortPlayerController::bHoldingObject 0xD20
  FortPlayerController::DBNOCarryInputComponent 0xD28
  FortPlayerController::HeldObjectsInputComponent 0xD30
  FortPlayerController::bWantsToSprint 0xD80
  FortPlayerController::bHoldingSprint 0xD80
  FortPlayerController::bSprintToggleable 0xD80
  FortPlayerController::bSprintByDefault 0xD80
  FortPlayerController::bSprintCancelsReload 0xD80
  FortPlayerController::bSprintWasCancelledByReload 0xD80
  FortPlayerController::bAutoRunOn 0xD80
  FortPlayerController::bUseHoldToSwapPickup 0xD80
  FortPlayerController::bTargetingToggleable 0xD81
  FortPlayerController::bTargetingToggleableWithTouch 0xD81
  FortPlayerController::bMovementDisabledDueToCancellableAction 0xD81
  FortPlayerController::bIsPlayerActivelyMoving 0xD81
  FortPlayerController::bPlaceHeldObjectPressed 0xD81
  FortPlayerController::InMovementCancellableAction 0xD84
  FortPlayerController::bAllowHoldForAmmoCrafting 0xD88
  FortPlayerController::bIsClientTimingOut 0xD89
  FortPlayerController::ClientTimeoutBlockInputTime 0xD8C
  FortPlayerController::LastMoveInputFrame 0xD98
  FortPlayerController::LastPressGamepadSprintTime 0xDA0
  FortPlayerController::bAutoRunWasHoldingForward 0xDA4
  FortPlayerController::bAtNameBaseScreen 0xDA5
  FortPlayerController::OnSetFirstPersonCamera 0xDA8
  FortPlayerController::CinematicCameraClassOverride 0xE28
  FortPlayerController::bOnPressExecuteJetpack 0xE30
  FortPlayerController::bShowHitMarkersForFriendlyFire 0xE50
  FortPlayerController::bServerSideHitMarkers 0xE51
  FortPlayerController::OnUiChoiceCompleted 0xE68
  FortPlayerController::OnRegainedFocus 0xE78
  FortPlayerController::OnOpenVoteDialog 0xE88
  FortPlayerController::bGamepadAbilityPending 0x113C
  FortPlayerController::bForceAllowCursorMode 0x113D
  FortPlayerController::bForceAllowCameraMode 0x113E
  FortPlayerController::bSuppressEventNotifications 0x1140
  FortPlayerController::LastSpotTime 0x11B0
  FortPlayerController::CurrentMarks 0x11C0
  FortPlayerController::LoopingUIFeedbackComponents 0x11D0
  FortPlayerController::PreviewAbility 0x1220
  FortPlayerController::IntensityGraphInfo 0x1240
  FortPlayerController::PIDValuesGraphInfo 0x1268
  FortPlayerController::PIDContributionsGraphInfo 0x1290
  FortPlayerController::AIDirectorDataManager 0x12B8
  FortPlayerController::MusicManager 0x12C0
  FortPlayerController::OnBuildPreviewMarkerVisibilityChanged 0x12C8
  FortPlayerController::OnWeakSpotReset 0x12D8
  FortPlayerController::bUsePredictedBuildingActors 0x12F8
  FortPlayerController::bRegisterPredictedBuildingActorsWithGrid 0x12F9
  FortPlayerController::bPredictedBuildingWallsHaveNoCollision 0x12FA
  FortPlayerController::PredictedActorLifespan 0x12FC
  FortPlayerController::PredictedBuildingSMActors 0x1300
  FortPlayerController::BuildPreviewModeInputComponent 0x1490
  FortPlayerController::BuildPreviewMarker 0x1498
  FortPlayerController::BuildPreviewMarkerExtraPiece 0x14A0
  FortPlayerController::bAllowBuildingPreviewAutoRotation 0x14E0
  FortPlayerController::bRequireTraceToExistingBuildingToSetContext 0x14E1
  FortPlayerController::bAllowTraceToExistingBuildingToSetContextToRedirectToBlockingBuilding 0x14E2
  FortPlayerController::bRequireTraceToExistingBuildingToSetContextExcludeCurrentContext 0x14E3
  FortPlayerController::TargetedBuilding 0x15A8
  FortPlayerController::TargetedVehicle 0x15B0
  FortPlayerController::ContextualConversionClass 0x15B8
  FortPlayerController::StartUpgradeSound 0x15C0
  FortPlayerController::HighlightedPrimaryBuildings 0x15E8
  FortPlayerController::HighlightedInteractionBuildings 0x15F8
  FortPlayerController::HighlightedPrimaryBuilding 0x1608
  FortPlayerController::BuildPreviewMarkerParentMaterial 0x1610
  FortPlayerController::BuildPreviewMarkerMIDs 0x1638
  FortPlayerController::BuildPreviewRotationIterations 0x1648
  FortPlayerController::bBuildPreviewMirrored 0x164C
  FortPlayerController::BuildPreviewMarkerOptionalAdjustment 0x1650
  FortPlayerController::bBuildFree 0x1654
  FortPlayerController::bCraftFree 0x168C
  FortPlayerController::CurrentCostInfoType 0x1690
  FortPlayerController::CurrentBuildableClass 0x1698
  FortPlayerController::PreviousBuildableClass 0x16A0
  FortPlayerController::CurrentResourceLevel 0x16A8
  FortPlayerController::CurrentResourceType 0x16A9
  FortPlayerController::LastBuildableStateData 0x16B0
  FortPlayerController::QueuedDamageNumbers 0x1780
  FortPlayerController::DamageNumbersActor 0x1790
  FortPlayerController::EditModeInputComponent 0x1798
  FortPlayerController::EditBuildingActor 0x17A0
  FortPlayerController::EditModeDistance 0x17A8
  FortPlayerController::LastBuildPreviewGridSnapLoc 0x17AC
  FortPlayerController::LastBuildPreviewGridSnapRot 0x17B8
  FortPlayerController::LastBuildPreviewGridSnapCentroid 0x17C4
  FortPlayerController::PickerInputComponent 0x17D0
  FortPlayerController::TrapPickerDecoHelper 0x17D8
  FortPlayerController::TouchEditResults 0x17E0
  FortPlayerController::bBuildingPlacementTraceSkipInitialPenetrationOfBuildingSMActor 0x17F1
  FortPlayerController::bBuildingPlacementTraceSkipInitialPenetrationOfStaticMesh 0x17F2
  FortPlayerController::ClientQuickBars 0x1838
  FortPlayerController::RecentlyRemovedQuickbarInfo 0x1848
  FortPlayerController::DelayedQuickBarActions 0x18A8
  FortPlayerController::ClientProcessedQuickBarActions 0x19C8
  FortPlayerController::bShouldForceDeleteDroppedItems 0x1A18
  FortPlayerController::QueuedItemsToDrop 0x1A40
  FortPlayerController::bAutoEquipBetterItems 0x1AE8
  FortPlayerController::WorldInventory 0x1AF0
  FortPlayerController::OutpostInventory 0x1AF8
  FortPlayerController::ViewTargetInventory 0x1B00
  FortPlayerController::bHasInitializedWorldInventory 0x1B54
  FortPlayerController::bHasInitializedHeroInventory 0x1B54
  FortPlayerController::bAccountInventoryWasUpdated 0x1B54
  FortPlayerController::bForceWorldInventoryUpdate 0x1B54
  FortPlayerController::bIsSavingGadgetLoadout 0x1B54
  FortPlayerController::BotPilot 0x1BF0
  FortPlayerController::BotManager 0x1C10
  FortPlayerController::ClientBotManagerClass 0x1C20
  FortPlayerController::CosmeticLoadoutPC 0x1C40
  FortPlayerController::LocalPawnCustomizationAssetLoader 0x1D90
  FortPlayerController::bDropWeaponsDuringAllMissionStates 0x1DB0
  FortPlayerController::LatestRewardReport 0x1DD0
  FortPlayerController::MyPlayerInfo 0x1E40
  FortPlayerController::UpdatedObjectiveStats 0x1E48
  FortPlayerController::bHasUnsavedPrimaryMissionProgress 0x1E58
  FortPlayerController::StatManager 0x1E98
  FortPlayerController::HeartbeatManager 0x1EA0
  FortPlayerController::StatEventManager 0x1EA8
  FortPlayerController::CachedPersistentGameplayStats 0x1EB0
  FortPlayerController::LastEmotePlayed 0x1ED0
  FortPlayerController::EmoteUsageCounts 0x1ED8
  FortPlayerController::AnalyticsBuildingWallTooLowLocations 0x1F28
  FortPlayerController::NearbyEmotingPawns 0x1F38
  FortPlayerController::NearbyEmotingPawnCount 0x1F88
  FortPlayerController::McpProfileGroup 0x1FD8
  FortPlayerController::CommonPublicMcpProfile 0x1FE0
  FortPlayerController::CommonCoreMcpProfile 0x1FE8
  FortPlayerController::MainMcpProfile 0x1FF0
  FortPlayerController::AthenaProfile 0x1FF8
  FortPlayerController::MetadataProfile 0x2000
  FortPlayerController::CreativeModeProfile 0x2008
  FortPlayerController::TutorialCompletedState 0x2010
  FortPlayerController::bShouldReceiveCriticalMatchBonus 0x2048
  FortPlayerController::OnPlayerChangedBuildMode 0x2050
  FortPlayerController::OnAutoRunEnabled 0x2060
  FortPlayerController::VoiceInputSourceEffectPresetChain 0x21D0
  FortPlayerController::LocationUnderReticle 0x226C
  FortPlayerController::bEnableVoiceChatPTT 0x2278
  FortPlayerController::bVoiceChatPTTTransmit 0x2278
  FortPlayerController::bInfiniteAmmo 0x2278
  FortPlayerController::bInfiniteConsumables 0x2278
  FortPlayerController::bInfiniteMagazine 0x2278
  FortPlayerController::bNoCoolDown 0x2278
  FortPlayerController::bInfiniteDurability 0x2278
  FortPlayerController::bUsePickers 0x2278
  FortPlayerController::bPickerOpen 0x2279
  FortPlayerController::bPickerEnabled 0x2279
  FortPlayerController::bCheatGhost 0x2279
  FortPlayerController::bCheatFly 0x2279
  FortPlayerController::bEnableShotLogging 0x2279
  FortPlayerController::bIsNearActiveEncounters 0x2279
  FortPlayerController::OverriddenBackpackSize 0x227C
  FortPlayerController::CurrentReplaySpotLight 0x2280
  FortPlayerController::AimHelpMode 0x2288
  FortPlayerController::JumpStaminaCost 0x228C
  FortPlayerController::CameraPrototypeName 0x2290
  FortPlayerController::bHideHudEnglishText 0x22C0
  FortPlayerController::bAutoChangeMaterial 0x22C1
  FortPlayerController::bServerAutoChangeMaterial 0x22C2
  FortPlayerController::bPeripheralLightingEnabled 0x22C3
  FortPlayerController::bRudderControlEnabled 0x22C4
  FortPlayerController::RudderDeadZone 0x22C8
  FortPlayerController::RudderMaxThrottle 0x22CC
  FortPlayerController::ActiveSprayInstances 0x22D0
  FortPlayerController::ActiveToyInstances 0x22E0
  FortPlayerController::ToySummonCounts 0x22F0
  FortPlayerController::bSyncPeripheralLightingWithEmoteMusic 0x2340
  FortPlayerController::bPushEmoteAudioDataToCosmeticMaterials 0x2341
  FortPlayerController::LastEmoteMusicFFT100hz 0x2344
  FortPlayerController::LastEmoteMusicFFT2000hz 0x2348
  FortPlayerController::EmoteMusicBeatThreshold 0x234C
  FortPlayerController::EmoteMusicEnvelopeBeatCount 0x2350
  FortPlayerController::bZeroingCameraRoll 0x24B8
  FortPlayerController::bTryPickupSwap 0x24B9
  FortPlayerController::bClientSideEditPrediction 0x24BA
  FortPlayerController::ClientSideEditPredictionTimeout 0x24BC
  FortPlayerController::PendingEnterEditModeActor 0x24C8
  FortPlayerController::RandomCharacterIndex 0x24D0
  FortPlayerController::AntiAddictionPlayTimeMultiplier 0x24D4
  FortPlayerController::bUsesWidgetForFPSDisplay 0x24D8
  FortPlayerController::bShowFPS 0x24D9
  FortPlayerController::OnShowFPSChange 0x24E0
  FortPlayerController::bShowTemperature 0x24F0
  FortPlayerController::OnShowTemperatureChange 0x24F8
  FortPlayerController::LockOnInfo 0x2554
  FortPlayerController::bLockPrimaryInputMethodToMouse 0x258C
  FortPlayerController::IndicatorManager 0x25A0
  FortPlayerController::bFinalXPUpdateFailed 0x25B8
  FortPlayerController::TestUserWidget 0x25C0
  FortPlayerController::PreviousStasisMode 0x25C8
  FortPlayerController::BattleMapSpectatorClass 0x25D0
  FortPlayerController::bReleaseBuildingContextOnPlace 0x25F5
  FortPlayerController::TurboPlaceFirstInterval 0x25F8
  FortPlayerController::TurboPlaceInterval 0x25FC
  FortPlayerController::bCreativeTurboDelete 0x2600
  FortPlayerController::TurboDeleteFirstInterval 0x2604
  FortPlayerController::TurboDeleteInterval 0x2608
  FortPlayerController::bTurboBuild 0x260D
  FortPlayerController::TurboBuildFirstInterval 0x2610
  FortPlayerController::TurboBuildRequestFailedInterval 0x2614
  FortPlayerController::TurboBuildInterval 0x2618
  FortPlayerController::FortControllerComponent_Telemetry 0x2628
  FortPlayerController::InventoryNetworkManagementComponent 0x2630
  FortPlayerController::InteractionComponent 0x2638
  FortPlayerController::QuickEditComponent 0x2640
  FortPlayerController::SmartBuildComponent 0x2648
  FortPlayerController::CollectionsComponent 0x2650
  FortPlayerController::PendingExecuteInventoryItemHandle 0x2658
  FortPlayerController::QuickHealItemPickerClass 0x2688
  FortPlayerController::OnPlayerSpawnedBuildingActor 0x2690
  FortPlayerController::MeshParentIds 0x26A0
  FortPlayerController::OnToggleFullscreenMap 0x26B0
  FortPlayerController::ForcedInputRotationSpeed 0x27A8
  FortPlayerController::PendingClientRestartPawn 0x27B0

  FortAthenaSKVehicle
  FortAthenaSKVehicle::WheelOffsetFR 0x15A0
  FortAthenaSKVehicle::WheelOffsetFL 0x15A4
  FortAthenaSKVehicle::WheelOffsetLimitF 0x15A8
  FortAthenaSKVehicle::WheelOffsetBR 0x15AC
  FortAthenaSKVehicle::WheelOffsetBL 0x15B0
  FortAthenaSKVehicle::WheelOffsetLimitB 0x15B4
  FortAthenaSKVehicle::WheelOffsetLerpPerSecondUp 0x15B8
  FortAthenaSKVehicle::WheelOffsetLerpPerSecondDown 0x15BC
  FortAthenaSKVehicle::AxleOffsetZ 0x15C0
  FortAthenaSKVehicle::AxleOffsetZ_B 0x15C4
  FortAthenaSKVehicle::AxleCenterF 0x15C8
  FortAthenaSKVehicle::AxleCenterB 0x15CC
  FortAthenaSKVehicle::AxleRollF 0x15D0
  FortAthenaSKVehicle::AxleRollB 0x15D4
  FortAthenaSKVehicle::WheelRotationFR 0x15D8
  FortAthenaSKVehicle::WheelRotationFL 0x15DC
  FortAthenaSKVehicle::WheelRotationBR 0x15E0
  FortAthenaSKVehicle::WheelRotationBL 0x15E4
  FortAthenaSKVehicle::WheelRotationVelocityFR 0x15E8
  FortAthenaSKVehicle::WheelRotationVelocityFL 0x15EC
  FortAthenaSKVehicle::WheelRotationVelocityBR 0x15F0
  FortAthenaSKVehicle::WheelRotationVelocityBL 0x15F4
  FortAthenaSKVehicle::WheelSpinFR 0x15F8
  FortAthenaSKVehicle::WheelSpinFL 0x15FC
  FortAthenaSKVehicle::WheelSpinBR 0x1600
  FortAthenaSKVehicle::WheelSpinBL 0x1604
  FortAthenaSKVehicle::WheelSpinVelocityFR 0x1608
  FortAthenaSKVehicle::WheelSpinVelocityFL 0x160C
  FortAthenaSKVehicle::WheelSpinVelocityBR 0x1610
  FortAthenaSKVehicle::WheelSpinVelocityBL 0x1614
  FortAthenaSKVehicle::WheelSpinDampingPerSecond 0x1618
  FortAthenaSKVehicle::bShouldDealDamage 0x161C

  StaticMeshComponent
  StaticMeshComponent::ForcedLodModel 0x488
  StaticMeshComponent::PreviousLODLevel 0x48C
  StaticMeshComponent::MinLOD 0x490
  StaticMeshComponent::SubDivisionStepSize 0x494
  StaticMeshComponent::StaticMesh 0x498
  StaticMeshComponent::WireframeColorOverride 0x4A0
  StaticMeshComponent::bEvaluateWorldPositionOffset 0x4A4
  StaticMeshComponent::bOverrideWireframeColor 0x4A4
  StaticMeshComponent::bOverrideMinLOD 0x4A4
  StaticMeshComponent::bOverrideNavigationExport 0x4A4
  StaticMeshComponent::bForceNavigationObstacle 0x4A4
  StaticMeshComponent::bDisallowMeshPaintPerInstance 0x4A4
  StaticMeshComponent::bIgnoreInstanceForTextureStreaming 0x4A4
  StaticMeshComponent::bOverrideLightMapRes 0x4A4
  StaticMeshComponent::bCastDistanceFieldIndirectShadow 0x4A5
  StaticMeshComponent::bOverrideDistanceFieldSelfShadowBias 0x4A5
  StaticMeshComponent::bUseSubDivisions 0x4A5
  StaticMeshComponent::bUseDefaultCollision 0x4A5
  StaticMeshComponent::bReverseCulling 0x4A5
  StaticMeshComponent::OverriddenLightMapRes 0x4A8
  StaticMeshComponent::DistanceFieldIndirectShadowMinVisibility 0x4AC
  StaticMeshComponent::DistanceFieldSelfShadowBias 0x4B0
  StaticMeshComponent::StreamingDistanceMultiplier 0x4B4
  StaticMeshComponent::LODData 0x4B8
  StaticMeshComponent::StreamingTextureData 0x4C8
  StaticMeshComponent::LightmassSettings 0x4D8

  FortCameraMode
  FortCameraMode::PlayerCamera 0x28
  FortCameraMode::TransitionTime 0x30
  FortCameraMode::TransitionOutTime 0x34
  FortCameraMode::bOverrideTransitionOutTime 0x38
  FortCameraMode::TransitionParams 0x3C
  FortCameraMode::bResetInterpolation 0x4C
  FortCameraMode::bShouldAllowBlendingWhenActive 0x4C
  FortCameraMode::bShouldAllowBlendingWhenInactive 0x4C
  FortCameraMode::bShouldPassViewTargetCheckOnTransition 0x4C

  FortCameraMode_ThirdPerson
  FortCameraMode_ThirdPerson::FOV 0x50
  FortCameraMode_ThirdPerson::CameraSpaceForwardDistance 0x54
  FortCameraMode_ThirdPerson::bClampCameraPitch 0x58
  FortCameraMode_ThirdPerson::bClampCameraYaw 0x59
  FortCameraMode_ThirdPerson::CameraPitchMin 0x5C
  FortCameraMode_ThirdPerson::CameraPitchMax 0x60
  FortCameraMode_ThirdPerson::CameraYawMin 0x64
  FortCameraMode_ThirdPerson::CameraYawMax 0x68
  FortCameraMode_ThirdPerson::CameraOrigin 0x6C
  FortCameraMode_ThirdPerson::CameraOriginSocketName 0x70
  FortCameraMode_ThirdPerson::CameraOriginInterpSpeed 0x78
  FortCameraMode_ThirdPerson::CameraLocationErrorConstraintBox 0x84
  FortCameraMode_ThirdPerson::ViewTargetSpaceViewOffset 0xA0
  FortCameraMode_ThirdPerson::ViewTargetSpaceViewOffset_Crouch 0xB0
  FortCameraMode_ThirdPerson::ViewTargetSpaceViewOffseInterpSpeed 0xC0
  FortCameraMode_ThirdPerson::CameraSpaceViewOffset 0xD0
  FortCameraMode_ThirdPerson::ViewTargetAlignmentFlipInterpDuration 0xE0
  FortCameraMode_ThirdPerson::bScaleViewOffsetByViewTargetScale 0xE4
  FortCameraMode_ThirdPerson::bSupportsShoulderSwap 0xE5
  FortCameraMode_ThirdPerson::LastCameraOrigin 0x118
  FortCameraMode_ThirdPerson::CameraOriginLocalOffset 0x124
  FortCameraMode_ThirdPerson::PenetrationBlendInTime 0x130
  FortCameraMode_ThirdPerson::PenetrationBlendOutTime 0x134
  FortCameraMode_ThirdPerson::bPreventPenetration 0x138
  FortCameraMode_ThirdPerson::bDoPredictiveAvoidance 0x139
  FortCameraMode_ThirdPerson::CollisionPushOutDistance 0x13C
  FortCameraMode_ThirdPerson::HidePawnPenetrationPercent 0x140
  FortCameraMode_ThirdPerson::LastAttachSocketName 0x178
  FortCameraMode_ThirdPerson::LastBasePOV 0x180
  FortCameraMode_ThirdPerson::DeltaBasePOV 0x7C0
  FortCameraMode_ThirdPerson::BlendAlpha 0xE00
  FortCameraMode_ThirdPerson::PenetrationAvoidanceFeelers 0xE18
  FortCameraMode_ThirdPerson::SafeLocToAimLineBlockedPct 0xE28
  FortCameraMode_ThirdPerson::AimLineToDesiredPosBlockedPct 0xE2C
  FortCameraMode_ThirdPerson::LastDrawDebugTime 0xE30
  FortCameraMode_ThirdPerson::LastViewTargetSpaceViewOffset 0xE34
  FortCameraMode_ThirdPerson::LastViewTargetAlignmentUp 0xE40
  FortCameraMode_ThirdPerson::ViewTargetAlignmentFlipInterpTime 0xE4C
  FortCameraMode_ThirdPerson::LastCameraPivot 0xE50
  FortCameraMode_ThirdPerson::CachedPitchLimitMin 0xE5C
  FortCameraMode_ThirdPerson::CachedPitchLimitMax 0xE60
  FortCameraMode_ThirdPerson::CachedYawLimitMin 0xE64
  FortCameraMode_ThirdPerson::CachedYawLimitMax 0xE68
  FortCameraMode_ThirdPerson::bLastViewTargetValidGroupEmoteLookTarget 0xE6C
  FortCameraMode_ThirdPerson::IgnoreActorForCameraPenetration 0xE70
  FortCameraMode_ThirdPerson::DebugActorsHitDuringCameraPenetration 0xE78
  FortCameraMode_ThirdPerson::bWasInVehicle 0xE88
  FortCameraMode_ThirdPerson::PreviousIgnoreActorForCameraPenetration 0xE90

  FortVehicleConfigs
  FortVehicleConfigs::NumWheelsTouchingGroundForWheelsOnGround 0x28
  FortVehicleConfigs::TimeToIdleBrake 0x2C
  FortVehicleConfigs::ChangeDirBrakeDelta 0x30
  FortVehicleConfigs::VehicleSleepCounter 0x34
  FortVehicleConfigs::VehicleMinFOV 0x38
  FortVehicleConfigs::VehicleMaxFOV 0x3C
  FortVehicleConfigs::VehicleMinFOVSpeed 0x40
  FortVehicleConfigs::VehicleMaxFOVSpeed 0x44
  FortVehicleConfigs::VehicleFOVInterpSpeed 0x48
  FortVehicleConfigs::CameraSpaceForwardDistanceOverride 0x4C
  FortVehicleConfigs::OffroadCamShakeClass 0x50
  FortVehicleConfigs::OffroadCameraShakeOscillationYAmplitude 0x58
  FortVehicleConfigs::OffroadCameraShakeOscillationZAmplitude 0x5C
  FortVehicleConfigs::OffroadCameraShakeMaxVehicleSpeed 0x60
  FortVehicleConfigs::OffroadCameraShakeOscillationRotationAmplitude 0x64
  FortVehicleConfigs::OffroadCameraShakeOscillationMinFrequency 0x68
  FortVehicleConfigs::OffroadCameraShakeOscillationMaxFrequency 0x6C
  FortVehicleConfigs::AcceleratingCamShakeClass 0x70
  FortVehicleConfigs::InteractDistanceScalar 0x78
  FortVehicleConfigs::MinFallDamageHeight 0x7C
  FortVehicleConfigs::MaxFallDamageHeight 0x80
  FortVehicleConfigs::MinFallDamage 0x84
  FortVehicleConfigs::MaxFallDamage 0x88
  FortVehicleConfigs::PlayerFallDamageMultiplier 0x8C
  FortVehicleConfigs::bDamageFriendlyVehicles 0x90
  FortVehicleConfigs::bDamageOtherVehicles 0x91
  FortVehicleConfigs::bDamageOwnVehicle 0x92
  FortVehicleConfigs::bDamageAllowedFromOtherVehicle 0x93
  FortVehicleConfigs::VehicleEjectCooldown 0x94
  FortVehicleConfigs::PlayerToSocketSweepRadius 0x98
  FortVehicleConfigs::VehicleGravity 0x9C
  FortVehicleConfigs::PlayerGravityMultiplier 0xA0
  FortVehicleConfigs::PassengerDamageOnDestruction 0xA4
  FortVehicleConfigs::MinFallDamageNormalScale 0xA8
  FortVehicleConfigs::DriverExitLaunchScalar 0xAC
  FortVehicleConfigs::DriverExitLaunchUpScalar 0xB0
  FortVehicleConfigs::DriverExitInAirLaunchScalar 0xB4
  FortVehicleConfigs::DriverExitInAirLaunchUpScalar 0xB8
  FortVehicleConfigs::PassengerExitLaunchScalar 0xBC
  FortVehicleConfigs::PassengerExitLaunchUpScalar 0xC0
  FortVehicleConfigs::PassengerExitInAirLaunchScalar 0xC4
  FortVehicleConfigs::PassengerExitInAirLaunchUpScalar 0xC8
  FortVehicleConfigs::bCanDoTricks 0xCC
  FortVehicleConfigs::bShouldDriverHaveReticle 0xCD
  FortVehicleConfigs::bSupportsWraps 0xCE
  FortVehicleConfigs::ExitVehicleCoolDown 0xD0
  FortVehicleConfigs::bShouldProtectFromFireDamage 0xD4
  FortVehicleConfigs::bInheritScale 0xD5
  FortVehicleConfigs::HoldToExitTime 0xD8
  FortVehicleConfigs::ForceExitZOffset 0xDC
  FortVehicleConfigs::bBlockBuilding 0xE0
  FortVehicleConfigs::bPreferDriverSeatWhenEmpty 0xE1
  FortVehicleConfigs::FireDamagePerSecond 0xE4
  FortVehicleConfigs::FireDamageTickRate 0xE8
  FortVehicleConfigs::bCanBeOnFire 0xEC
  FortVehicleConfigs::DamageableParts 0xF0
  FortVehicleConfigs::ToggleablePartNames 0x100
  FortVehicleConfigs::UnoccupiedAutoDestroyTime 0x110
  FortVehicleConfigs::HUDTopSpeed 0x138
  FortVehicleConfigs::PlayerFacingName 0x140
  FortVehicleConfigs::WheelRotationRange 0x150
  FortVehicleConfigs::VehicleFrontLowLateralFrictionMultiplier 0x154
  FortVehicleConfigs::VehicleRearLowLateralFrictionMultiplier 0x158
  FortVehicleConfigs::VehicleFrontHighLateralFrictionMultiplier 0x15C
  FortVehicleConfigs::VehicleRearHighLateralFrictionMultiplier 0x160
  FortVehicleConfigs::LowToHighFrictionDuration 0x164
  FortVehicleConfigs::UphillIncline 0x168
  FortVehicleConfigs::ReverseToForwardFrontFriction 0x16C
  FortVehicleConfigs::ReverseToForwardRearFriction 0x170
  FortVehicleConfigs::ReverseToForwardMaxSpeed 0x174
  FortVehicleConfigs::TireModDataMapping 0x178
  FortVehicleConfigs::HonkTimeMax 0x1C8
  FortVehicleConfigs::HonkCooldownMax 0x1CC
  FortVehicleConfigs::HonkTimePerHonk 0x1D0

  FortWeapon
  FortWeapon::OnWeaponRateOfFireChanged 0x248
  FortWeapon::OnPressTrigger 0x270
  FortWeapon::OnReleaseTrigger 0x280
  FortWeapon::TimeToEquip 0x2B0
  FortWeapon::bIsEquippingWeapon 0x2C0
  FortWeapon::bIsReloadingWeapon 0x2C1
  FortWeapon::bIsChargingWeapon 0x2C2
  FortWeapon::bDisableEquipAnimation 0x2C3
  FortWeapon::bIsAimingConsumable 0x2C5
  FortWeapon::OnLocalAmmoChanged 0x2E8
  FortWeapon::OnLocalReloadStarted 0x2F8
  FortWeapon::OnLocalReloadCancelled 0x308
  FortWeapon::OnLocalTargetingChanged 0x318
  FortWeapon::OnSecondaryAbilityToggled 0x328
  FortWeapon::OnWeaponFireAudioVisuals 0x338
  FortWeapon::OnReticleColorChanged 0x360
  FortWeapon::bUseAttributeCaching 0x384
  FortWeapon::WeaponData 0x388
  FortWeapon::CosmeticOverrideWeaponData 0x390
  FortWeapon::bImpactFXAttachedToHitActor 0x398
  FortWeapon::GameplayAbilityBehaviorDistanceData 0x3A0
  FortWeapon::HitNotifyAudioBank 0x3B0
  FortWeapon::bRemoveAbilitiesWhenRemovedFromInventory 0x3D0
  FortWeapon::GrantedAbilityRemovalPolicy 0x3D1
  FortWeapon::EquippedWeaponDestroyWrapperRepCounter 0x418
  FortWeapon::PersistentFXStartTime 0x4E8
  FortWeapon::MinimumTimeForPersistentFX 0x4EC
  FortWeapon::OverrideItemWrapSoftPtr 0x4F0
  FortWeapon::WeaponReduceMeshWorkSetting 0x528
  FortWeapon::bWeaponSupportsQuartzGunfire 0x529
  FortWeapon::QuartzGunfireComp 0x530
  FortWeapon::bShouldDrawNativeReticle 0x538
  FortWeapon::ReticleImage 0x540
  FortWeapon::AutoFireReticleImage 0x548
  FortWeapon::ReticleDefaultColor 0x550
  FortWeapon::ReticleEnemyColor 0x554
  FortWeapon::ReticleBuildingColor 0x558
  FortWeapon::ReticleNoTargetColor 0x55C
  FortWeapon::HitNotifyReticleImage 0x560
  FortWeapon::HitNotifyLocationReticleImage 0x568
  FortWeapon::CriticalHitNotifyLocationReticleImage 0x570
  FortWeapon::ReticleCenterImage 0x578
  FortWeapon::ReticleCenterPerfectAimImage 0x580
  FortWeapon::ReticleInvalidTargetImage 0x588
  FortWeapon::MuzzleBlockedReticleImage 0x590
  FortWeapon::ReticleAltCenterImage 0x598
  FortWeapon::ReticleOuterImage 0x5A0
  FortWeapon::ReticleAltOuterImage 0x5A8
  FortWeapon::ReticleDefaultPrimaryStrikeAngle 0x5B0
  FortWeapon::ReticleDefaultSecondaryStrikeAngle 0x5B4
  FortWeapon::bSupportsAutofireAtReticleTarget 0x5B8
  FortWeapon::CameraBase3PClass 0x5C0
  FortWeapon::CameraTargeting3PClass 0x5C8
  FortWeapon::CameraBase1PClass 0x5D0
  FortWeapon::CameraTargeting1PClass 0x5D8
  FortWeapon::DestroyedSound 0x5E0
  FortWeapon::OutOfAmmoSound 0x5E8
  FortWeapon::ReloadSounds 0x5F0
  FortWeapon::PrimaryFireSound1P 0x608
  FortWeapon::PrimaryFireSound 0x610
  FortWeapon::PrimaryFireStopSound1P 0x628
  FortWeapon::PrimaryFireStopSound 0x630
  FortWeapon::SecondaryFireSound 0x648
  FortWeapon::SecondaryFireStopSound 0x660
  FortWeapon::ChargeFireSound1P 0x678
  FortWeapon::ChargeFireSound 0x690
  FortWeapon::TargetingStartSound 0x6A8
  FortWeapon::TargetingEndSound 0x6B0
  FortWeapon::PrimaryFireSoundFadeOutTime 0x6B8
  FortWeapon::ImpactPhysicalSurfaceSounds 0x6C0
  FortWeapon::ImpactPhysicalSurfaceEffects 0x7A8
  FortWeapon::ImpactNiagaraPhysicalSurfaceEffectAssets 0x888
  FortWeapon::ImpactCameraShake 0x898
  FortWeapon::PrimaryForceFeedbackEffect 0x8A0
  FortWeapon::SecondaryForceFeedbackEffect 0x8A8
  FortWeapon::PrimaryImpactForceFeedbackEffect 0x8B0
  FortWeapon::SecondaryImpactForceFeedbackEffect 0x8B8
  FortWeapon::ImpactNiagaraPhysicalSurfaceEffectInstances 0x8C0
  FortWeapon::DataStoreManager 0x8D0
  FortWeapon::FireAudioChannels 0x8D8
  FortWeapon::ReloadAudioChannels 0x8F8
  FortWeapon::TargetingAudioChannels 0x910
  FortWeapon::SoundIndicatorComponent 0x920
  FortWeapon::CurrentGunFireIndex 0x928
  FortWeapon::WeaponMesh 0x930
  FortWeapon::AllWeaponMeshes 0x938
  FortWeapon::DefaultWeaponMaterials 0x948
  FortWeapon::OriginalMaterialMap 0x958
  FortWeapon::FireAudioChannelWantsToPlay 0x9A8
  FortWeapon::WrapSectionMask 0x9B8
  FortWeapon::bUsingSecondaryFireAudio 0x9BC
  FortWeapon::bHasCachedAdditionalMeshes 0x9BD
  FortWeapon::CurrentReticleColor 0x9C0
  FortWeapon::CurrentDamageStartLocation 0x9C4
  FortWeapon::CurrentAdjustedAimDirection 0x9D0
  FortWeapon::FireFXSignificance 0x9DC
  FortWeapon::LastFireTime 0x9F4
  FortWeapon::LastFireTimeVerified 0x9F8
  FortWeapon::bIsPlayingFireFX 0x9FC
  FortWeapon::bFireFXTriggered 0x9FD
  FortWeapon::TimerIntervalAdjustment 0xA00
  FortWeapon::InputQueueTimePercent 0xA04
  FortWeapon::bAllowTargeting 0xA08
  FortWeapon::bIsTargeting 0xA09
  FortWeapon::LastTargetingTransitionTime 0xA0C
  FortWeapon::TargetSourceOffset 0xA10
  FortWeapon::TargetSourceOffsetWhileCrouched 0xA1C
  FortWeapon::TargetSourceOffsetWhileTargeting 0xA28
  FortWeapon::bTraceThroughPawns 0xA34
  FortWeapon::bTraceThroughWorld 0xA35
  FortWeapon::TraceThroughPawnsLimit 0xA38
  FortWeapon::TraceThroughBuildingsLimit 0xA3C
  FortWeapon::TraceThroughLandscapeLimit 0xA40
  FortWeapon::bUseProjectileTrace 0xA44
  FortWeapon::bUseVariableFocalDistanceTargeting 0xA45
  FortWeapon::bUseWeaponTraceForReticle 0xA46
  FortWeapon::ProjectilePitchOffset 0xA48
  FortWeapon::LastReloadTime 0xA4C
  FortWeapon::LastSuccessfulReloadTime 0xA50
  FortWeapon::CurrentReloadDuration 0xA54
  FortWeapon::ItemEntryGuid 0xA5C
  FortWeapon::TrackerGuid 0xA6C
  FortWeapon::WeaponLevel 0xA7C
  FortWeapon::AmmoCount 0xA80
  FortWeapon::PhantomReserveAmmo 0xA84
  FortWeapon::BurstFireCounter 0xA90
  FortWeapon::ChargeTime 0xA94
  FortWeapon::AccumulatedChargeTime 0xA98
  FortWeapon::StartChargeGameplayCue 0xA9C
  FortWeapon::MaxChargeGameplayCue 0xAA4
  FortWeapon::OutOfAmmoTextOverrideFailTag 0xAAC
  FortWeapon::NoSpareAmmoToReloadTextOverrideFailTag 0xAB4
  FortWeapon::CurrentShotLogIndex 0xABC
  FortWeapon::ShotLogFlags 0xAC0
  FortWeapon::bInitializedWeaponItem 0xAD0
  FortWeapon::bPendingDestroyDueToDurabilityOrStackCount 0xAD0
  FortWeapon::bCompletedAppliedAlterationsLoad 0xAD1
  FortWeapon::bCompletedWeaponLoad 0xAD1
  FortWeapon::bIsCosmeticLimited 0xAD1
  FortWeapon::bReplicatedAppliedAlterationsWithNoInstigator 0xAD1
  FortWeapon::bShouldFullyApplyVariantsOnEquip 0xAD1
  FortWeapon::bSecondaryFireAlwaysCancelSwimSprint 0xAD1
  FortWeapon::ChargeStatusPack 0xAD4
  FortWeapon::AttachedTrajectoryIndicator 0xAE4
  FortWeapon::ActiveAbility 0xAF0
  FortWeapon::PrimaryAbilitySpecHandle 0xAF8
  FortWeapon::SecondaryAbilitySpecHandle 0xAFC
  FortWeapon::ReloadAbilitySpecHandle 0xB00
  FortWeapon::ImpactAbilitySpecHandle 0xB04
  FortWeapon::ReticleTraceOverrideSpecHandle 0xB08
  FortWeapon::EquippedAbilityHandles 0xB10
  FortWeapon::EquippedAbilitySetHandles 0xB20
  FortWeapon::AppliedAlterations 0xB30
  FortWeapon::WeaponModSlots 0xB40
  FortWeapon::EquippedWeaponModSlots 0xB50
  FortWeapon::PreviousWeaponVariants 0xB60
  FortWeapon::AppliedItemWrap 0x1188
  FortWeapon::CachedFXManager 0x1190
  FortWeapon::CachedSignificanceManager 0x1198
  FortWeapon::MuzzleSocketName 0x11A0
  FortWeapon::MuzzleFalloffSocketName 0x11A8
  FortWeapon::WeaponHandSocketNameOverride 0x11B0
  FortWeapon::LeftHandWeaponHandSocketNameOverride 0x11B8
  FortWeapon::WeaponHandSocketPartOverrides 0x11C0
  FortWeapon::bForceOverrideGenerateOverlapEvents 0x11D8
  FortWeapon::MaxWeaponSwitchNetworkWaitTime 0x1264
  FortWeapon::LastFireAbilityTime 0x1268
  FortWeapon::EquipAnimation 0x12A0
  FortWeapon::ReloadAnimation 0x12A8
  FortWeapon::CustomReloadAnimationPerAmmoToFill 0x12B0
  FortWeapon::PrimaryAbilityAnimation 0x12C0
  FortWeapon::SecondaryAbilityAnimation 0x12C8
  FortWeapon::WeaponEquipMontage 0x12D0
  FortWeapon::WeaponReloadMontage 0x12D8
  FortWeapon::CustomWeaponReloadMontagePerAmmoToFill 0x12E0
  FortWeapon::WeaponPrimaryAbilityMontage 0x12F0
  FortWeapon::WeaponSecondaryAbilityMontage 0x12F8
  FortWeapon::PoseOffsetAnimSequence 0x1300
  FortWeapon::PoseOffsetAnimSequenceFemaleOverride 0x1308
  FortWeapon::WeaponCoreAnimation 0x1310
  FortWeapon::WeaponPawnAnimSet 0x1318
  FortWeapon::WeaponPawnAnimLayerOverlayClass 0x1320
  FortWeapon::WeaponAdditiveAnimSet 0x1328
  FortWeapon::WeaponPawnAnimsetOverride 0x1330
  FortWeapon::UnableToPerformActionMontageOverride 0x1368
  FortWeapon::ActiveFireMode 0x1370
  FortWeapon::FireModeData_HipFire 0x1398
  FortWeapon::FireModeData_AimDownSight 0x13C0
  FortWeapon::FireModeData_Override 0x13E8
  FortWeapon::ItemWrapModifier 0x1420
  FortWeapon::LockOnTargetCandidate 0x1440
  FortWeapon::bIgnoreTryToFireSlotCooldownRestriction 0x1449
  FortWeapon::bFireConsumableAnalyticEvent 0x144B
  FortWeapon::OnWeaponHudKeyActionUpdated 0x1450
  FortWeapon::HudKeyActionData 0x1460

  Character
  Character::Mesh 0x288
  Character::CharacterMovement 0x290
  Character::CapsuleComponent 0x298
  Character::BasedMovement 0x2A0
  Character::ReplicatedBasedMovement 0x2D0
  Character::AnimRootMotionTranslationScale 0x300
  Character::BaseTranslationOffset 0x304
  Character::BaseRotationOffset 0x310
  Character::ReplicatedServerLastTransformUpdateTimeStamp 0x320
  Character::ReplayLastTransformUpdateTimeStamp 0x324
  Character::ReplicatedMovementMode 0x328
  Character::bInBaseReplication 0x329
  Character::CrouchedEyeHeight 0x32C
  Character::bIsCrouched 0x330
  Character::bProxyIsJumpForceApplied 0x330
  Character::bPressedJump 0x330
  Character::bClientUpdating 0x330
  Character::bClientWasFalling 0x330
  Character::bClientResimulateRootMotion 0x330
  Character::bClientResimulateRootMotionSources 0x330
  Character::bSimGravityDisabled 0x330
  Character::bClientCheckEncroachmentOnNetUpdate 0x331
  Character::bServerMoveIgnoreRootMotion 0x331
  Character::bWasJumping 0x331
  Character::JumpKeyHoldTime 0x334
  Character::JumpForceTimeRemaining 0x338
  Character::ProxyJumpForceStartedTime 0x33C
  Character::JumpMaxHoldTime 0x340
  Character::JumpMaxCount 0x344
  Character::JumpCurrentCount 0x348
  Character::JumpCurrentCountPreJump 0x34C
  Character::OnReachedJumpApex 0x358
  Character::MovementModeChangedDelegate 0x378
  Character::OnCharacterMovementUpdated 0x388
  Character::SavedRootMotion 0x398
  Character::ClientRootMotionParams 0x3D0
  Character::RootMotionRepMoves 0x410
  Character::RepRootMotion 0x420

  FortPawn
  FortPawn::bUseBaseChanged 0x548
  FortPawn::bIgnoreNextFallingDamage 0x548
  FortPawn::bAllowDeathFromFallingDamage 0x548
  FortPawn::bIsDying 0x548
  FortPawn::bPlayedDying 0x548
  FortPawn::bIsHiddenForDeath 0x548
  FortPawn::bIsKnockedback 0x548
  FortPawn::bIsStaggered 0x549
  FortPawn::bCanCapsuleBeUsedForTargeting 0x549
  FortPawn::bUseLineTestForDamageZoneBoneDetection 0x549
  FortPawn::bMovingEmote 0x549
  FortPawn::bMovingEmoteForwardOnly 0x549
  FortPawn::bMovingEmoteFollowingOnly 0x549
  FortPawn::bMovingEmoteSkipLandingFX 0x54A
  FortPawn::bIsInvulnerable 0x54A
  FortPawn::bSpotted 0x54A
  FortPawn::bRegisterWithAISight 0x54A
  FortPawn::bRegisterWithAimAssist 0x54A
  FortPawn::bPrimaryInputHeld 0x54A
  FortPawn::bSecondaryInputHeld 0x54A
  FortPawn::bPrimaryInputQueued 0x54A
  FortPawn::bWeaponActivated 0x54B
  FortPawn::bIsInGoop 0x54B
  FortPawn::bReplicatedIsInGoop 0x54B
  FortPawn::bIsSliding 0x54B
  FortPawn::bIsSwinging 0x54B
  FortPawn::bSwingingAttached 0x54B
  FortPawn::SwingAttachLocation 0x54C
  FortPawn::SwingAttachLocationUpdateDistanceThreshold 0x558
  FortPawn::SynchedActionLocation 0x55C
  FortPawn::SynchedActionRotation 0x570
  FortPawn::bSkipAnalogJump 0x580
  FortPawn::FootstepTraceTypeQuery 0x581
  FortPawn::FootstepSurfaceType 0x582
  FortPawn::SoundIndicatorComponent 0x588
  FortPawn::UroShiftBucket 0x598
  FortPawn::bUpdateMeshComponentUpdateFlagOnServer 0x599
  FortPawn::bUROCanTieToLODs 0x599
  FortPawn::bPostProcessNavLocation 0x599
  FortPawn::bHealthSynced 0x599
  FortPawn::bWeaponHolstered 0x599
  FortPawn::bSkipReticleColorTrace 0x599
  FortPawn::bPrioritizePawnCollisionsOnAbilityTargetSelectionVisibilityTest 0x599
  FortPawn::bTreatAsPawnForHitMarkers 0x59A
  FortPawn::bDisplayPawnHitMarkersForChildActors 0x59A
  FortPawn::bUsesStats 0x59A
  FortPawn::bAllowBuildingActorTeleport 0x59A
  FortPawn::bIsDBNO 0x59A
  FortPawn::bWasDBNOOnDeath 0x59A
  FortPawn::bCachedIsInAthena 0x59A
  FortPawn::bShouldUseCharacterMovementIdleFastPath 0x59A
  FortPawn::CurrentMovementStyle 0x59B
  FortPawn::ControlRecoveryBehavior 0x59C
  FortPawn::TeleportCounter 0x59D
  FortPawn::PawnStatHandle 0x5A0
  FortPawn::SlidingFriction 0x5B0
  FortPawn::SlidingBrakingDeceleration 0x5B4
  FortPawn::StormShieldComponent 0x5B8
  FortPawn::OnStormShieldComponentCreated 0x5C0
  FortPawn::PushSize 0x5D0
  FortPawn::LastSurfaceTraceTime 0x5DC
  FortPawn::LastSurfaceTraceLocation 0x5E0
  FortPawn::PawnUniqueID 0x618
  FortPawn::CurrentWeapon 0x620
  FortPawn::PreviousWeapon 0x628
  FortPawn::CurrentWeaponList 0x630
  FortPawn::PreviousAbilityWeaponNameForTelemetry 0x640
  FortPawn::WeaponHandSocketName 0x650
  FortPawn::LeftHandWeaponHandSocketName 0x658
  FortPawn::SpawnSpot 0x660
  FortPawn::DeathTags 0x668
  FortPawn::SpawnImmunityTime 0x688
  FortPawn::CurrentWaterBody 0x690
  FortPawn::bShouldSupportSurfaceSwimming 0x698
  FortPawn::ReplicatedWaterBody 0x6A0
  FortPawn::IncomingPickups 0x6A8
  FortPawn::PickupDirectionData 0x6B8
  FortPawn::bIsStunned 0x6C8
  FortPawn::VortexParams 0x6D0
  FortPawn::bIsInVortex 0x720
  FortPawn::bReplicatedIsInVortex 0x720
  FortPawn::CurrentSkyTube 0x728
  FortPawn::ReplicatedSkyTube 0x730
  FortPawn::OverlappedSkyTubes 0x738
  FortPawn::bPrioritizeEarlierTubes 0x748
  FortPawn::OnSkyTubeChanged 0x770
  FortPawn::AdditiveCringeCount 0x780
  FortPawn::AdditiveCringeDuration 0x784
  FortPawn::bSupportsDamageNumbersAtHitLocation 0x788
  FortPawn::PushMomentum 0x78C
  FortPawn::LocalSpin 0x79C
  FortPawn::bTurnTransitionActiveAndControllingRotation 0x7A1
  FortPawn::DeathCueTag 0x800
  FortPawn::DeathStatTags 0x808
  FortPawn::DeathHitSocket 0x818
  FortPawn::OnPlayerStartDBNO 0x820
  FortPawn::OnDBNOStateChanged 0x830
  FortPawn::DefaultLifespanAfterDeath 0x840
  FortPawn::TeamBeaconMaxDist 0x844
  FortPawn::TeamBeaconTextColor 0x848
  FortPawn::LastTakeHitTimeTimeout 0x84C
  FortPawn::LastDamagedTime 0x850
  FortPawn::CurrentlyAttachedWeapon 0x858
  FortPawn::CachedNavFloor 0x860
  FortPawn::MaxFootstepDistance 0x868
  FortPawn::DBNOLandingSound 0x870
  FortPawn::DefaultFootstepSound 0x878
  FortPawn::DefaultFastFootstepSound 0x880
  FortPawn::DefaultLandingSound 0x888
  FortPawn::DefaultHardLandingSound 0x890
  FortPawn::DefaultJumpSound 0x898
  FortPawn::DefaultHitNotifyAudioBank 0x8A0
  FortPawn::DefaultSwimmingAudioBank 0x8A8
  FortPawn::LineTestForDamageZoneBoneDetectionRadius 0x8B0
  FortPawn::DamageZones 0x8B8
  FortPawn::DamageZoneActiveBitMask 0x918
  FortPawn::TargettingZOffset 0x91C
  FortPawn::JumpFlashCountPacked 0x920
  FortPawn::LandingFlashCountPacked 0x921
  FortPawn::EmoteAudioComps 0x928
  FortPawn::FrontEndEmoteAudioAttenuation 0x978
  FortPawn::InGameEmoteAudioAttenuation 0x980
  FortPawn::InGameEmoteSoundEffectSoundPresetChain 0x988
  FortPawn::EmoteMeshComps 0x990
  FortPawn::EmotePropActors 0x9E0
  FortPawn::EmoteParticleSystemComps 0xA30
  FortPawn::EmoteCount 0xA80
  FortPawn::LastEmoteTime 0xA84
  FortPawn::LastEmoteEndTime 0xA88
  FortPawn::LastEmoteItemDef 0xA90
  FortPawn::LastReplicatedEmoteExecuted 0xA98
  FortPawn::bFireBlockedByEmoteCooldown 0xAA0
  FortPawn::EmoteToFireCooldownTime 0xAA4
  FortPawn::EmoteWalkSpeed 0xAA8
  FortPawn::AdditionalModifierDefinitions 0xAB0
  FortPawn::OnPawnTeleported 0xAC0
  FortPawn::OnPawnLanded 0xAD0
  FortPawn::OnPawnStartedEmote 0xAE0
  FortPawn::OnPawnStoppedEmote 0xAF0
  FortPawn::OnHitPawn 0xB00
  FortPawn::OnDied 0xB10
  FortPawn::OnDeathEffects 0xB20
  FortPawn::OnDamaged 0xB60
  FortPawn::OnDidDamage 0xB70
  FortPawn::FootstepBank 0xB80
  FortPawn::CachedStepSurfaceNormal 0xB98
  FortPawn::FoleyFootstepContext 0xBA8
  FortPawn::FoleyHitContext 0xBB0
  FortPawn::FortFootstepComponent 0xBB8
  FortPawn::OnWeaponEquippedDelegate 0xBC0
  FortPawn::OnWeaponUnEquippedDelegate 0xBD0
  FortPawn::OnWeaponAttachmentChangedDelegate 0xBE0
  FortPawn::HealthRegenDelayGameplayEffect 0xBF0
  FortPawn::HealthRegenGameplayEffect 0xBF8
  FortPawn::ShieldRegenDelayGameplayEffect 0xC00
  FortPawn::ShieldRegenGameplayEffect 0xC08
  FortPawn::CurrentWeaponAnimLayerOverlayClass 0xC10
  FortPawn::OnHolsteredEvent 0xC18
  FortPawn::OnUnholsteredEvent 0xC28
  FortPawn::WeaponHolsterCounter 0xC50
  FortPawn::WeaponHolsterIds 0xC58
  FortPawn::StaySpottedTime 0xC68
  FortPawn::SpottedEvent 0xC6C
  FortPawn::DefaultFeedback 0xC78
  FortPawn::ActiveSoundIndicators 0xC80
  FortPawn::DefaultSoundTrackingVisual 0xC90
  FortPawn::SoundTrackingVisibilityTags 0xC98
  FortPawn::PriorityModifiers 0xCB8
  FortPawn::VocalChords 0xD08
  FortPawn::bIsDisconnectedPawn 0xD70
  FortPawn::MaxHealthApplicationHandle 0xD74
  FortPawn::MaxHealthApplicationGameplayEffect 0xD80
  FortPawn::HealthSet 0xD88
  FortPawn::ControlResistanceSet 0xD90
  FortPawn::DamageSet 0xD98
  FortPawn::MovementSet 0xDA0
  FortPawn::AdvancedMovementSet 0xDA8
  FortPawn::OnAbilityDecisionWindowStackUpdated 0xDB8
  FortPawn::AbilitySystemComponent 0xDC8
  FortPawn::DecisionWindowStack 0xDD0
  FortPawn::GameplayTags 0xDE0
  FortPawn::DisplayName 0xE00
  FortPawn::Damagers 0xE18
  FortPawn::DamageDone 0xE28
  FortPawn::TotalDamageDoneTrackers 0xE38
  FortPawn::TargetDamageDoneTrackers 0xE48
  FortPawn::TotalDamageTakenTrackers 0xE58
  FortPawn::TargetDamageTakenTrackers 0xE68
  FortPawn::DamageDoneLastAtTime 0xE78
  FortPawn::DamageTakenLastAtTime 0xE7C
  FortPawn::LastHitTime 0xE80
  FortPawn::TotalPlayerDamageDealt 0xE84
  FortPawn::HealthBarIndicator 0xE88
  FortPawn::CurrentCalloutTag 0xE90
  FortPawn::CalloutEntries 0xE98
  FortPawn::HealthBarWidth 0xEA8
  FortPawn::HealthBarHeightMultiplier 0xEAC
  FortPawn::SpottedBrush 0xEC0
  FortPawn::SpottedIconOffset 0xF70
  FortPawn::ClientNonRenderedAnimUpdateRate 0xF7C
  FortPawn::MaxEvalRateForInterpolation 0xF80
  FortPawn::AnimUpdateRateVisibleMaxDistanceFactor 0xF88
  FortPawn::LODToFrameSkipMap 0xF98
  FortPawn::CurrentSentence 0xFF8
  FortPawn::OnPawnHealthChanged 0x10D8
  FortPawn::OnPawnMaxOvershieldChanged 0x10E8
  FortPawn::AccumulatedBatchData_Shared 0x10F8
  FortPawn::AccumulatedBatchData_NonShared 0x1140
  FortPawn::BatchedGameplayCueParameters 0x1158
  FortPawn::ReplayItemActions 0x1218
  FortPawn::HidingVisibilityTags 0x1258
  FortPawn::HidingTransitionVisibilityTags 0x1278
  FortPawn::PegasusTimelineCollector 0x1298
  FortPawn::AILODComponent 0x12A0
  FortPawn::ClientAILODSettings 0x12C8
  FortPawn::FallbackTag 0x1350
  FortPawn::DebugType 0x1358
  FortPawn::RecordedGunshots 0x1368
  FortPawn::OnPawnComponentAttachedEvent 0x13F8

  FortPlayerPawn
  constexpr auto VehicleInputStateReliable = 0x1678; // FFortAthenaVehicleInputStateReliable
			constexpr auto bHasDisableSprintTag = 0x167a; // char : 1
			constexpr auto bIsWaterJump = 0x167a; // char : 1
			constexpr auto bDisableSwimSprintCancel = 0x167a; // char : 1
			constexpr auto bIsNearSafeZoneEdge = 0x167a; // char : 1
			constexpr auto bIsSprintJump = 0x167a; // char : 1
			constexpr auto bIsSwimmingAnimLayerLinked = 0x167a; // char : 1
			constexpr auto bDoSafeZoneCleanup = 0x167a; // char : 1
			constexpr auto bPlayingSafeZoneEffects = 0x167a; // char : 1
			constexpr auto bIsWaterSprintBoost = 0x167b; // char : 1
			constexpr auto bIsWaterSprintBoostPending = 0x167b; // char : 1
			constexpr auto bPlayingPassengerToPassengerAnimation = 0x167b; // char : 1
			constexpr auto bPlayingDriverToPassengerAnimation = 0x167b; // char : 1
			constexpr auto bIsTargeting = 0x167b; // char : 1
			constexpr auto bIsTargetingConsumableThrow = 0x167b; // char : 1
			constexpr auto bIsSwappingCharacterParts = 0x167c; // char : 1
			constexpr auto bBalloonMovementActivated = 0x167c; // char : 1
			constexpr auto bIsScriptedBot = 0x167c; // char : 1
			constexpr auto bBuildHotfix = 0x167c; // char : 1
			constexpr auto FortPlayerPawnLightingChannels = 0x167d; // FLightingChannels
			constexpr auto StasisMode = 0x167f; // EFortPawnStasisMode
			constexpr auto BuildingState = 0x1681; // EFortBuildingState
			constexpr auto AccelerationZPack = 0x1682; // int8_t
			constexpr auto ParachuteDirectionalSpeedMultiplierCurve = 0x16a0; // UCurveFloat*
			constexpr auto SkydivingDirectionalSpeedMultiplierCurve = 0x16a8; // UCurveFloat*
			constexpr auto BallooningDirectionalSpeedMultiplierCurve = 0x16b0; // UCurveFloat*
			constexpr auto DirectionalSpeedMultiplierCurve = 0x16b8; // UCurveFloat*
			constexpr auto LastCustomizationTimestamp = 0x16c0; // float
			constexpr auto MinimumTimeBetweenSteps = 0x16c4; // float
			constexpr auto LastStepTime = 0x16c8; // float
			constexpr auto OnFootstepEvent = 0x16d0; // FMulticastInlineDelegate
			constexpr auto OnPawnEnterWater = 0x16e0; // FMulticastInlineDelegate
			constexpr auto OnPawnExitWater = 0x16f0; // FMulticastInlineDelegate
			constexpr auto OnPawnExitSwinging = 0x1718; // FMulticastInlineDelegate
			constexpr auto bIsInWaterVolume = 0x1728; // bool
			constexpr auto bNotifyBlueprintWhenLandscapeTeleporting = 0x1729; // bool
			constexpr auto CachedTeamControllingRC = 0x172a; // char
			constexpr auto BalloonActiveCount = 0x172b; // char
			constexpr auto bParachuteDeployFixedVerticalDistance = 0x172c; // char : 1
			constexpr auto bIsSkydiving = 0x172d; // bool
			constexpr auto bIsParachuteOpen = 0x172e; // bool
			constexpr auto bIsSkydivingFromLaunchPad = 0x172f; // char : 1
			constexpr auto bIsInSlipperyMovement = 0x172f; // char : 1
			constexpr auto bPendingSkydiveLaunch = 0x172f; // char : 1
			constexpr auto bIsSkydivingFromBus = 0x172f; // char : 1
			constexpr auto bLocalIsParachuteForcedOpen = 0x172f; // char : 1
			constexpr auto bLocalIsSkydiving = 0x172f; // char : 1
			constexpr auto bIsParachuteForcedOpen = 0x172f; // char : 1
			constexpr auto bIsPedestalHero = 0x1730; // char : 1
			constexpr auto bInGliderRedeploy = 0x1730; // char : 1
			constexpr auto bLocalInGliderRedeploy = 0x1730; // char : 1
			constexpr auto bIsProxySimulationTimedOut = 0x1730; // char : 1
			constexpr auto bIsSlopeSliding = 0x1730; // char : 1
			constexpr auto bIsBelowAutoDeployTestHeight = 0x1730; // char : 1
			constexpr auto bReplicatedIsInSlipperyMovement = 0x1730; // char : 1
			constexpr auto bBeingRepossessed = 0x1731; // char : 1
			constexpr auto bInitAbilitySystemComponentFromPlayerState = 0x1731; // char : 1
			constexpr auto bStartedInteractSearch = 0x1731; // char : 1
			constexpr auto bPawnLODDirty = 0x1731; // char : 1
			constexpr auto bIsUsingJetpack = 0x1731; // char : 1
			constexpr auto bIsPlayingEmote = 0x1731; // char : 1
			constexpr auto bShowingOverdriveEffect = 0x1731; // char : 1
			constexpr auto bIsRespawning = 0x1731; // char : 1
			constexpr auto bCanShowDefaultSkin = 0x1732; // char : 1
			constexpr auto bDisabledTetheringSupport = 0x1732; // char : 1
			constexpr auto bIsInFrontEndHologram = 0x1732; // char : 1
			constexpr auto bHasWaterParticleSystem = 0x1732; // char : 1
			constexpr auto bInitializedPostRepPlayerState = 0x1732; // char : 1
			constexpr auto bIsRespawningInAir = 0x1732; // char : 1
			constexpr auto HeldObject = 0x1784; // TWeakObjectPtr<AActor>
			constexpr auto bForceMoveRelativeToCameraRotation = 0x17a0; // char : 1
			constexpr auto bIsWaitingForEmoteInteraction = 0x17a0; // char : 1
			constexpr auto bIsEmoteLeader = 0x17a0; // char : 1
			constexpr auto bShouldSyncAnimationWithEmoteLeader = 0x17a0; // char : 1
			constexpr auto bShouldJitterAnimationSyncWithEmoteLeader = 0x17a0; // char : 1
			constexpr auto bDoubleFileEmoteSecondLine = 0x17a0; // char : 1
			constexpr auto bEmoteUsesSecondaryFire = 0x17a0; // char : 1
			constexpr auto bLockGroupEmoteLeaderRotation = 0x17a0; // char : 1
			constexpr auto GroupEmoteLookTarget = 0x17a8; // AFortPlayerPawn*
			constexpr auto GroupEmoteTailTarget = 0x17b0; // AFortPlayerPawn*
			constexpr auto GroupEmoteFollowers = 0x17b8; // TArray<AFortPlayerPawn*>
			constexpr auto GroupEmoteAnimOffset = 0x1824; // float
			constexpr auto GroupEmoteLeaderRotationYawOffset = 0x1828; // float
			constexpr auto GroupEmoteLookTargetRotationLeader = 0x1830; // FRotator
			constexpr auto GroupEmoteMaximumZDifference = 0x1860; // float
			constexpr auto OnGroupEmoteSyncValueChanged = 0x1868; // FMulticastInlineDelegate
			constexpr auto OnGroupEmoteFollowerJoined = 0x1878; // FMulticastInlineDelegate
			constexpr auto OnGroupEmoteFollowerLeft = 0x1888; // FMulticastInlineDelegate
			constexpr auto OnGroupEmoteSecondaryFirePressed = 0x1898; // FMulticastInlineDelegate
			constexpr auto GroupEmoteSyncValue = 0x18a8; // char
			constexpr auto GroupEmoteSoundValue = 0x18a9; // char
			constexpr auto GroupEmoteParticleValue = 0x18aa; // char
			constexpr auto TransformationMontage = 0x18b0; // UAnimMontage*
			constexpr auto TransformationMontageStartTime = 0x18b8; // float
			constexpr auto CurrentMontagerLeader = 0x1918; // UAnimMontage*
			constexpr auto CurrentSyncedMontage = 0x1920; // UAnimMontage*
			constexpr auto bCharacterPartsCastIndirectShadows = 0x1928; // char : 1
			constexpr auto CharacterGender = 0x192a; // EFortCustomGender
			constexpr auto CharacterBodyType = 0x192b; // EFortCustomBodyType
			constexpr auto JumpLastActivatedTime = 0x193c; // float
			constexpr auto PreviousPosition = 0x1940; // FVector
			constexpr auto PreviousVelocity = 0x1958; // FVector
			constexpr auto ReplicatedCustomMeshHeightAdjustTarget = 0x19b8; // uint16_t
			constexpr auto UnburrowLaunchXYSpeed = 0x19bc; // float
			constexpr auto UnburrowLaunchZSpeed = 0x19c0; // float
			constexpr auto VehicleInputStateUnreliable = 0x1a08; // FFortAthenaVehicleInputStateUnreliable
			constexpr auto bIsInAnyStorm = 0x1a88; // char : 1
			constexpr auto bIsInsideSafeZone = 0x1a88; // char : 1
			constexpr auto SafeZoneAppliedGE = 0x1a98; // UGameplayEffect*
			constexpr auto DisableSlideGameplayEffectClass = 0x1ac8; // UGameplayEffect*
			constexpr auto SelfReviveGameplayEffect = 0x1ad0; // UGameplayEffect*
			constexpr auto TeammateReviveGameplayEffect = 0x1ad8; // UGameplayEffect*
			constexpr auto SetByCallerReviveHealth = 0x1ae0; // FScalableFloat
			constexpr auto DBNOInteractionCollisionProfile = 0x1b08; // FName
			constexpr auto DBNOInteractionBoxExtent = 0x1b10; // FVector
			constexpr auto DBNODeferTime = 0x1b28; // float
			constexpr auto DBNOInteractCollisionComponent = 0x1b30; // UBoxComponent*
			constexpr auto EventReviveTag = 0x1b38; // FGameplayTag
			constexpr auto AggroRangeOverride = 0x1b3c; // float
			constexpr auto SetByCallerReviveSignalInStorm = 0x1b40; // float
			constexpr auto ArmoredInterface = 0x1b48; // TScriptInterface<IFortArmoredInterface>
			constexpr auto LastBuildingMetadata = 0x1b58; // UBuildingEditModeMetadata*
			constexpr auto SprintCancelTime = 0x1b68; // float
			constexpr auto WaterSprintBoostAllowedTimer = 0x1b70; // float
			constexpr auto bHasStartedFloating = 0x1bfc; // bool
			constexpr auto ZiplineState = 0x1c00; // FZiplinePawnState
			constexpr auto ZiplineJumpDampening = 0x1c40; // FCurveTableRowHandle
			constexpr auto ZiplineJumpStrength = 0x1c50; // FCurveTableRowHandle
			constexpr auto ZiplineJumpActivateDelay = 0x1c60; // FScalableFloat
			constexpr auto ZiplineRentryProtectionDelay = 0x1c88; // FScalableFloat
			constexpr auto ZiplineSocketZOffset = 0x1cb0; // float
			constexpr auto ZiplineAnimBlueprintClass = 0x1cb8; // UAnimInstance*
			constexpr auto TimeBeforeZiplineStateDeactivated = 0x1cc0; // float
			constexpr auto ZiplineStateChanged = 0x1cd0; // FMulticastInlineDelegate
			constexpr auto ZiplineSpeedFactorTarget = 0x1ce0; // float
			constexpr auto ZiplineSpeedFactor = 0x1ce4; // float
			constexpr auto EnableSwimSprintDiveCooldown = 0x1cf0; // FScalableFloat
			constexpr auto SwimSprintDiveCooldown = 0x1d18; // FScalableFloat
			constexpr auto SwimDiveBoostTimeThreshold = 0x1d40; // FScalableFloat
			constexpr auto ClientSwimDiveInputTime = 0x1d68; // float
			constexpr auto bCanPredictJumpApex = 0x1d6c; // bool
			constexpr auto AbilityAITargets = 0x1d78; // TArray<AFortAIPawn*>
			constexpr auto UnableToPerformActionMontage = 0x1da0; // UAnimMontage*
			constexpr auto UnableToPerformActionSound = 0x1da8; // USoundBase*
			constexpr auto MoveSoundStimulusBroadcastInterval = 0x1db0; // float
			constexpr auto EmoteStartTime = 0x1e94; // float
			constexpr auto EmoteRandomNum = 0x1e98; // float
			constexpr auto bPlayingPassengerToDriverAnimation = 0x1eb0; // bool
			constexpr auto VehicleSpeedAtTimeOfJump = 0x1ec8; // float
			constexpr auto VehicleStateRep = 0x1ed0; // FVehiclePawnState
			constexpr auto InteractingPCRep = 0x1f00; // AFortPlayerControllerGameplay*
			constexpr auto VehicleStateLocal = 0x1f08; // FVehiclePawnState
			constexpr auto VehicleLastTick = 0x1f38; // AActor*
			constexpr auto OnVehicleStateChangedEvent = 0x1f58; // FMulticastInlineDelegate
			constexpr auto TetherComponent = 0x1f68; // UFortPawnComponent_Tether*
			constexpr auto PendingTetherLaunch = 0x1f70; // float
			constexpr auto TetherJumpLastTime = 0x1fc0; // float
			constexpr auto bSupportsTetheredMovement = 0x1fc4; // bool
			constexpr auto BalloonRope = 0x1fc8; // ABuildingGameplayActor*
			constexpr auto OnPossessedProp = 0x1fd0; // FMulticastInlineDelegate
			constexpr auto PossessedProp = 0x1fe0; // ABuildingGameplayActorPlayerPropAttachment*
			constexpr auto SlopeCameraOffsetFrameCounter = 0x2018; // int64_t
			constexpr auto SlopeCameraOffsetInterpolator = 0x2020; // FVectorRK4SpringInterpolator
			constexpr auto LargeBodyTypeTargetingOffset = 0x2080; // FVector
			constexpr auto VehicleInputComponent = 0x2180; // UInputComponent*
			constexpr auto BluePrintPlaceAnimation = 0x2190; // UAnimMontage*
			constexpr auto BluePrintEditAnimation = 0x2198; // UAnimMontage*
			constexpr auto OnStartedInteractSearch = 0x21a8; // FMulticastInlineDelegate
			constexpr auto OnEndedInteractSearch = 0x21b8; // FMulticastInlineDelegate
			constexpr auto OnAttemptedInstantInteractSearch = 0x21c8; // FMulticastInlineDelegate
			constexpr auto EmoteInteractionCollisionProfile = 0x21d8; // FName
			constexpr auto EmoteInteractionBoxExtent = 0x21e0; // FVector
			constexpr auto EmoteInteractCollisionComponent = 0x21f8; // UBoxComponent*
			constexpr auto OnPartChanged = 0x2200; // FMulticastInlineDelegate
			constexpr auto BlueprintPaperMID = 0x2240; // UMaterialInstanceDynamic*
			constexpr auto BlueprintPaperPulseTimeline = 0x2248; // FTimeline
			constexpr auto AccessoryColorSwatchHandler0x7 = 0x22d8; // UCustomColorComponent*
			constexpr auto Hero = 0x2310; // UFortHero*
			constexpr auto OvrHeroType = 0x2318; // TWeakObjectPtr<UFortHeroType>
			constexpr auto DisplayContext = 0x2320; // EFortPawnDisplayContext
			constexpr auto HACK_CustomPRIComponent = 0x2340; // UCustomPlayerComponent*
			constexpr auto CharacterParts0x7 = 0x2348; // UCustomCharacterPart*
			constexpr auto CharacterColorSwatches0x2 = 0x2380; // UCustomColorSwatch*
			constexpr auto CharacterPartColorSwatches0x7 = 0x2390; // UCustomColorSwatch*
			constexpr auto CharacterCharms0x4 = 0x23c8; // UAthenaCharmItemDefinition*
			constexpr auto RequiredVariantParts = 0x23e8; // TArray<UCustomCharacterPart*>
			constexpr auto CharacterPartSkeletalMeshComponents0x7 = 0x2400; // USkeletalMeshComponentBudgeted*
			constexpr auto CharacterCharmActors = 0x2438; // TArray<AFortPlayerCharm*>
			constexpr auto CharacterPartSMHiddenRefCount0x7 = 0x2448; // int8_t
			constexpr auto BaseCosmeticLoadout = 0x2450; // FFortAthenaLoadout
			constexpr auto AppliedCosmeticLoadout = 0x25b0; // FFortAthenaLoadout
			constexpr auto AppliedSwaps = 0x2710; // TArray<FFortAppliedSwapItemAndVariantData>
			constexpr auto CosmeticLoadout = 0x2770; // FFortAthenaLoadout
			constexpr auto ServerLoadoutChangeSync = 0x28d0; // uint32_t
			constexpr auto bAllowClientLoadoutChangeSync = 0x28d8; // bool
			constexpr auto OnMaterialOverrideApplied = 0x2900; // FMulticastInlineDelegate
			constexpr auto OnMaterialOverrideCleared = 0x2910; // FMulticastInlineDelegate
			constexpr auto MaterialOverrides = 0x2920; // TArray<FFortPawnMaterialOverride>
			constexpr auto LocalMaterialOverrides = 0x2930; // TArray<FFortPawnMaterialOverride>
			constexpr auto MaterialOverrideStateMap = 0x2940; // TMap<USceneComponent*, FFortPawnMaterialOverrideState>
			constexpr auto PreviousCharacterParts0x7 = 0x2990; // UCustomCharacterPart*
			constexpr auto CharacterPartModifiers0x7 = 0x29c8; // ACustomCharacterPartModifier*
			constexpr auto RepCharPartAnimMontageInfo = 0x2a00; // FFortCharacterPartsRepMontageInfo
			constexpr auto ClientObservedStats = 0x2a20; // FFortClientObservedStatArray
			constexpr auto AnimBPOverride = 0x2b70; // UAnimInstance*
			constexpr auto OriginalAnimBP = 0x2b78; // UAnimInstance*
			constexpr auto OnCrouchStartSound = 0x2b80; // USoundBase*
			constexpr auto OnCrouchEndSound = 0x2b88; // USoundBase*
			constexpr auto FootstepBankOverride = 0x2b90; // UFortFootstepAudioBank*
			constexpr auto OriginalFootstepBank = 0x2b98; // UFortFootstepAudioBank*
			constexpr auto CachedFootStepIndex = 0x2ba0; // int32_t
			constexpr auto AnimSetOverride = 0x2ba8; // UFortWeaponAnimSet*
			constexpr auto AnimLayersOverride = 0x2bb0; // TArray<UAnimInstance*>
			constexpr auto PreviousAnimLayersOverride = 0x2bc0; // TArray<UAnimInstance*>
			constexpr auto QueuedAutoPickups = 0x2bd0; // TArray<AFortPickup*>
			constexpr auto IgnoreActors = 0x2be0; // TArray<FIgnoreCollisionActor>
			constexpr auto AutoPickupDropRepickupDelay = 0x2bf8; // FScalableFloat
			constexpr auto CarriedObjectAttachmentSocket = 0x2c30; // FName
			constexpr auto PickupSpeedMultiplier = 0x2c34; // float
			constexpr auto MiniMapIconBrush = 0x2c40; // FSlateBrush
			constexpr auto AboveBelowMiniMapIconBrush = 0x2d10; // FSlateBrush
			constexpr auto FarOffMiniMapIconBrush = 0x2de0; // FSlateBrush
			constexpr auto DBNOMiniMapIconBrush = 0x2eb0; // FSlateBrush
			constexpr auto MinimapIconColorSelf = 0x2f80; // FLinearColor
			constexpr auto MinimapIconColorTeammate = 0x2f90; // FLinearColor
			constexpr auto MinimapIconColorEnemy = 0x2fa0; // FLinearColor
			constexpr auto MaxIndicatorVisibilityDistForEnemies = 0x2fb0; // float
			constexpr auto MaxIndicatorVisibilityDistForAllies = 0x2fb4; // float
			constexpr auto DBNOHoisterData = 0x3038; // FFortDBNOCarryHoisterData
			constexpr auto DBNOHoistee = 0x3048; // AFortPlayerPawn*
			constexpr auto DBNOHoisterAnimSet = 0x3050; // UFortWeaponAnimSet*
			constexpr auto DBNOHoisteeAnimClass = 0x3058; // UAnimInstance*
			constexpr auto ThrowCarriedPlayerStrengthXY = 0x3060; // float
			constexpr auto ThrowCarriedPlayerStrengthZ = 0x3064; // float
			constexpr auto DropCarriedPlayerForwardOffset = 0x3068; // float
			constexpr auto DropCarriedPlayerHeightOffset = 0x306c; // float
			constexpr auto DropCarriedPlayerTraceHeight = 0x3070; // float
			constexpr auto bAllowDBNOCarry = 0x3074; // bool
			constexpr auto bAllowDBNOCarryEnemies = 0x3075; // bool
			constexpr auto bIsBeingDBNOCarried = 0x3076; // bool
			constexpr auto bIsDBNOCarrying = 0x3077; // bool
			constexpr auto bRequestedThrowCarriedPlayer = 0x3078; // bool
			constexpr auto PackedReplicatedSlopeAngles = 0x3088; // uint16_t
			constexpr auto OnDBNOHoisterChangedDelegate = 0x3090; // FMulticastInlineDelegate
			constexpr auto OnRevivedFromDBNODelegate = 0x30a0; // FMulticastInlineDelegate
			constexpr auto OnNewPlayerState = 0x30b0; // FMulticastInlineDelegate
			constexpr auto OnAbilitySystemComponentInitialized = 0x30c0; // FMulticastInlineDelegate
			constexpr auto OnPreInvalidateAbilitySystemComponent = 0x30d0; // FMulticastInlineDelegate
			constexpr auto OnFinishedCharacterCustomization = 0x3100; // FMulticastInlineDelegate
			constexpr auto OnCrouchInputJustPressed = 0x3110; // FMulticastInlineDelegate
			constexpr auto CustomizationAssetLoader = 0x3120; // UFortCustomizationAssetLoader*
			constexpr auto SpawnParticles = 0x3168; // UParticleSystem*
			constexpr auto SpawnSound = 0x3170; // USoundBase*
			constexpr auto bIsLocalPlayer = 0x317c; // char : 1
			constexpr auto bDamagedEnemy = 0x3184; // char : 1
			constexpr auto OnDamageComboIncrement = 0x31a0; // FMulticastInlineDelegate
			constexpr auto OnDamageComboReset = 0x31b0; // FMulticastInlineDelegate
			constexpr auto PlayerStatus = 0x31c8; // uint32_t
			constexpr auto AccelerationPack = 0x31cc; // uint16_t
			constexpr auto RepAnimMontageInfo = 0x31d0; // FGameplayAbilityRepAnimMontage
			constexpr auto RepAnimMontageStartSection = 0x3208; // int32_t
			constexpr auto bNetMovementPrioritized = 0x320c; // char : 1
			constexpr auto LandingMontagePair = 0x3210; // FReplicatedMontagePair
			constexpr auto PriorVariantData = 0x3230; // FPreviouslyAppliedVariantData
			constexpr auto TempWeaponsStack = 0x32b8; // TArray<UFortWorldItemDefinition*>
			constexpr auto RootMotionInterruptNotifyStack = 0x32c8; // TArray<UFortAnimNotifyState_RootMotionInterrupt*>
			constexpr auto RootMotionInterruptMontageStack = 0x32d8; // TArray<UAnimMontage*>
			constexpr auto VisibilityComponent = 0x3320; // UFortVisibilityComponent*
			constexpr auto BlendablesPostProcessComp = 0x3328; // UPostProcessComponent*
			constexpr auto bUseControllerRotationYawToRestore = 0x3334; // char : 1
			constexpr auto OnBeginSkydivingEvent = 0x3338; // FMulticastInlineDelegate
			constexpr auto OnEndSkydivingEvent = 0x3348; // FMulticastInlineDelegate
			constexpr auto OnBeginParachuteMovementEvent = 0x3358; // FMulticastInlineDelegate
			constexpr auto OnParachuteSpawned = 0x3368; // FMulticastInlineDelegate
			constexpr auto OnEndParachuteMovementEvent = 0x3378; // FMulticastInlineDelegate
			constexpr auto OnBallooningGravityCeilingChanged = 0x3388; // FMulticastInlineDelegate
			constexpr auto OnEnteredAircraft = 0x3398; // FMulticastInlineDelegate
			constexpr auto OnPawnPossessed = 0x33a8; // FMulticastInlineDelegate
			constexpr auto OnPawnUnpossessed = 0x33b8; // FMulticastInlineDelegate
			constexpr auto OnEmoteInteracted = 0x33c8; // FMulticastInlineDelegate
			constexpr auto OnSafeZoneOccupancyChangedEvent = 0x33d8; // FMulticastInlineDelegate
			constexpr auto OnHeldObjectPickedUp = 0x33e8; // FMulticastInlineDelegate
			constexpr auto OnHeldObjectDropped = 0x33f8; // FMulticastInlineDelegate
			constexpr auto CustomMovementIndicators = 0x3408; // TMap<EFortCustomMovement, UTexture*>
			constexpr auto CurrentGliderOpenSound = 0x3468; // USoundBase*
			constexpr auto CurrentGliderOpenAudioComponent = 0x3470; // TWeakObjectPtr<UAudioComponent>
			constexpr auto CurrentGliderCloseSound = 0x3478; // USoundBase*
			constexpr auto CurrentGliderCloseAudioComponent = 0x3480; // TWeakObjectPtr<UAudioComponent>
			constexpr auto bParachuteLockedOpen = 0x3494; // bool
			constexpr auto bLocalParachuteLockedOpen = 0x3495; // bool
			constexpr auto AttachmentMesh = 0x3498; // FRepFortMeshAttachment
			constexpr auto AttachmentMeshComponent = 0x34a8; // USkeletalMeshComponentBudgeted*
			constexpr auto BotScriptedBehavior = 0x34b0; // UFortPawnScriptedBehavior*
			constexpr auto IgnoredWaterBodies = 0x34d0; // TArray<AFortWaterBodyActor*>
			constexpr auto UnderwaterDamageComponent = 0x34e0; // UFortUnderwaterDamageComponent*
			constexpr auto SlipperySlopeParams = 0x34e8; // FSlipperySlopeParams
			constexpr auto GliderClass = 0x36a0; // UAthenaGliderItemDefinition*
			constexpr auto PetState = 0x36b8; // AFortPlayerPetRepState*
			constexpr auto CosmeticPetInstance = 0x36c0; // AFortPlayerPet*
			constexpr auto GliderSpawnComponent = 0x36d8; // UFortGliderSpawnComponent*
			constexpr auto ParachuteAttachment = 0x36e0; // AFortPlayerParachute*
			constexpr auto GliderOverrideStack = 0x36f0; // TArray<UAthenaGliderItemDefinition*>
			constexpr auto bResetGliderOverrideOnLanding = 0x3710; // bool
			constexpr auto ParachuteDeployTraceForGroundDistance = 0x3718; // FScalableFloat
			constexpr auto LaunchPadParachuteDeployTraceForGroundDistance = 0x3740; // FScalableFloat
			constexpr auto LaunchPadParachuteDeployTraceForDownwardSpeed = 0x3768; // FScalableFloat
			constexpr auto ParachuteDeployVelocityBlend = 0x3790; // FScalableFloat
			constexpr auto ParachuteCooldownToOpen = 0x37b8; // float
			constexpr auto ParachuteCooldownToClose = 0x37bc; // float
			constexpr auto GliderRedeployAllowedRow = 0x37c0; // FScalableFloat
			constexpr auto GliderRedeployLateralVelocityMultiplierRow = 0x37e8; // FScalableFloat
			constexpr auto GliderRedeployHeighLimitRow = 0x3810; // FScalableFloat
			constexpr auto BalloonFallDamageThresholdVelocityZ = 0x3838; // FScalableFloat
			constexpr auto DefaultLinkedAnimGraphAnimBlueprintClass = 0x3860; // UAnimInstance*
			constexpr auto PreDrivingAnimBP = 0x3868; // UAnimInstance*
			constexpr auto CurrentVehicleAnimLayerOverlayClass = 0x3870; // UAnimInstance*
			constexpr auto CurrentSwimmingAnimLayerOverlayClass = 0x3878; // UAnimInstance*
			constexpr auto DefaultSwimmingAnimLayerOverlayClass = 0x3880; // UAnimInstance*
			constexpr auto TimeBeforeSwimmingLayerDeactivated = 0x3890; // float
			constexpr auto ParachuteAudioLoop = 0x3898; // UAudioComponent*
			constexpr auto ParachuteAndSkydiveAudioFadeInTime = 0x38a0; // float
			constexpr auto ParachuteAndSkydiveAudioFadeOutTime = 0x38a4; // float
			constexpr auto SkydiveAudioLoop = 0x38a8; // UAudioComponent*
			constexpr auto SoundOnParachuteForcedOpen = 0x38b0; // USoundBase*
			constexpr auto SkydivingLoop1P = 0x38b8; // USoundBase*
			constexpr auto SkydivingLoop3P = 0x38c0; // USoundBase*
			constexpr auto ParachuteOpenLoop1P = 0x38c8; // USoundBase*
			constexpr auto ParachuteOpenLoop3P = 0x38d0; // USoundBase*
			constexpr auto SwimmingAudioLoop = 0x38d8; // UAudioComponent*
			constexpr auto SwimmingAudioFadeOutTime = 0x38e0; // float
			constexpr auto SwimmingAudioInterpSpeed = 0x38e4; // float
			constexpr auto SoundOnSwimmingLoop = 0x38e8; // USoundBase*
			constexpr auto RemoteViewData32 = 0x3940; // uint32_t
			constexpr auto LastQuickBarSwitchRequestTime = 0x3958; // float
			constexpr auto CrouchStartTime = 0x395c; // float
			constexpr auto CrouchEndTime = 0x3960; // float
			constexpr auto CrouchLerpTime = 0x3964; // float
			constexpr auto MeleeAbilityCooldown = 0x3968; // float
			constexpr auto bDisallowInterrogation = 0x396c; // bool
			constexpr auto bDisallowInterrogationOnNPC = 0x396d; // bool
			constexpr auto bDisallowInterrogationCreative = 0x396e; // bool
			constexpr auto bHideBodyOnDeathRequested = 0x396f; // char : 1
			constexpr auto ControlledRCPawn = 0x3970; // TWeakObjectPtr<AFortRemoteControlledPawnAthena>
			constexpr auto StoredControlRotation = 0x3978; // FRotator
			constexpr auto FacialTypeOverride = 0x3994; // EFortFacialAnimTypes
			constexpr auto GhostModeExitStartTime = 0x3998; // float
			constexpr auto GhostModeExitDuration = 0x399c; // float
			constexpr auto CachedReferencesByName = 0x3ad8; // TMap<FName, FFortPlayerPawnObjectReference>
			constexpr auto PSC_PlayerInWater = 0x3b28; // UParticleSystemComponent*
			constexpr auto PSC_PlayerInWaterSurfaceSwimming = 0x3b30; // UParticleSystemComponent*
			constexpr auto NiagaraPlayerInWaterBasicAsset = 0x3b38; // UNiagaraSystem*
			constexpr auto NiagaraPlayerInWaterSwimmingAsset = 0x3b40; // UNiagaraSystem*
			constexpr auto NiagaraPlayerWaterHandSplashAsset = 0x3b48; // UNiagaraSystem*
			constexpr auto NiagaraPlayerWaterFootSplashAsset = 0x3b50; // UNiagaraSystem*
			constexpr auto NiagaraPlayerWaterLargePlayerSplashAsset = 0x3b58; // UNiagaraSystem*
			constexpr auto NiagaraPlayerWaterBoostAsset = 0x3b60; // UNiagaraSystem*
			constexpr auto FootSplashLeftSocketName = 0x3b68; // FName
			constexpr auto FootSplashRightSocketName = 0x3b6c; // FName
			constexpr auto NiagaraPlayerStandingInWater = 0x3b70; // UFXSystemComponent*
			constexpr auto NiagaraPlayerSwimmingInWater = 0x3b78; // UFXSystemComponent*
			constexpr auto NiagaraPlayerHandSplashInWater = 0x3b80; // UFXSystemComponent*
			constexpr auto NiagaraPlayerFootSplashInWaterLeft = 0x3b88; // UFXSystemComponent*
			constexpr auto NiagaraPlayerFootSplashInWaterRight = 0x3b90; // UFXSystemComponent*
			constexpr auto NiagaraPlayerJumpSplashInWater = 0x3b98; // UFXSystemComponent*
			constexpr auto NiagaraPlayerWaterBoost = 0x3ba0; // UFXSystemComponent*
			constexpr auto bWaterFootSplashActive = 0x3ba8; // char : 1
			constexpr auto bEnableWaterInteractionEffects = 0x3ba8; // char : 1
			constexpr auto OnActivateAbility = 0x3bb0; // FMulticastInlineDelegate
			constexpr auto OnFiringRangedWeapon = 0x3bc0; // FMulticastInlineDelegate
			constexpr auto ConsecutiveWeakSpotResourceBonus = 0x3bd0; // FScalableFloat
			constexpr auto LastHitWeakSpotResourceBonus = 0x3bf8; // FScalableFloat
			constexpr auto CustomInteractionWidget = 0x3c28; // UWidget*
			constexpr auto ConvertComponent = 0x3c48; // UFortPawnComponent_Convert*
			constexpr auto AffiliationComponent = 0x3c50; // UFortActorComponent_Affiliation*
			constexpr auto bUseViewRotationForCameraOrigin = 0x3c59; // char : 1

  FortItemDefinition
  FortItemDefinition::OnItemCountChanged 0x48
  FortItemDefinition::Rarity 0x68
  FortItemDefinition::ItemType 0x69
  FortItemDefinition::PrimaryAssetIdItemTypeOverride 0x6A
  FortItemDefinition::FilterOverride 0x6B
  FortItemDefinition::Tier 0x6C
  FortItemDefinition::MaxTier 0x6D
  FortItemDefinition::Access 0x6E
  FortItemDefinition::bIsAccountItem 0x6F
  FortItemDefinition::bNeverPersisted 0x6F
  FortItemDefinition::bAllowMultipleStacks 0x6F
  FortItemDefinition::bAutoBalanceStacks 0x6F
  FortItemDefinition::bForceAutoPickup 0x6F
  FortItemDefinition::bInventorySizeLimited 0x6F
  FortItemDefinition::ItemTypeNameOverride 0x70
  FortItemDefinition::DisplayName 0x88
  FortItemDefinition::ShortDescription 0xA0
  FortItemDefinition::Description 0xB8
  FortItemDefinition::DisplayNamePrefix 0xD0
  FortItemDefinition::SearchTags 0xE8
  FortItemDefinition::GiftBoxGroupName 0x100
  FortItemDefinition::GameplayTags 0x108
  FortItemDefinition::AutomationTags 0x128
  FortItemDefinition::SecondaryCategoryOverrideTags 0x148
  FortItemDefinition::TertiaryCategoryOverrideTags 0x168
  FortItemDefinition::MaxStackSize 0x188
  FortItemDefinition::PurchaseItemLimit 0x1B0
  FortItemDefinition::FrontendPreviewScale 0x1D8
  FortItemDefinition::TooltipClass 0x1E0
  FortItemDefinition::StatList 0x208
  FortItemDefinition::RatingLookup 0x230
  FortItemDefinition::WidePreviewImage 0x240
  FortItemDefinition::SmallPreviewImage 0x268
  FortItemDefinition::LargePreviewImage 0x290
  FortItemDefinition::DisplayAssetPath 0x2B8
  FortItemDefinition::PopupDetailsTag 0x2D0
  FortItemDefinition::Series 0x2E0
  FortItemDefinition::FrontendPreviewPivotOffset 0x2E8
  FortItemDefinition::FrontendPreviewInitialRotation 0x2F4
  FortItemDefinition::FrontendPreviewMeshOverride 0x300
  FortItemDefinition::FrontendPreviewSkeletalMeshOverride 0x328

  World
  World::PersistentLevel 0x30
  World::NetDriver 0x38
  World::LineBatcher 0x40
  World::PersistentLineBatcher 0x48
  World::ForegroundLineBatcher 0x50
  World::NetworkManager 0x58
  World::PhysicsCollisionHandler 0x60
  World::ExtraReferencedObjects 0x68
  World::PerModuleDataObjects 0x78
  World::StreamingLevels 0x88
  World::StreamingLevelsToConsider 0x98
  World::StreamingLevelsPrefix 0xC0
  World::CurrentLevelPendingVisibility 0xD0
  World::CurrentLevelPendingInvisibility 0xD8
  World::DemoNetDriver 0xE0
  World::MyParticleEventManager 0xE8
  World::DefaultPhysicsVolume 0xF0
  World::bAreConstraintsDirty 0x116
  World::NavigationSystem 0x120
  World::AuthorityGameMode 0x128
  World::GameState 0x130
  World::AISystem 0x138
  World::AvoidanceManager 0x140
  World::Levels 0x148
  World::LevelCollections 0x158
  World::OwningGameInstance 0x190
  World::ParameterCollectionInstances 0x198
  World::CanvasForRenderingToTarget 0x1A8
  World::CanvasForDrawMaterialToRenderTarget 0x1B0
  World::PhysicsField 0x228
  World::LWILastAssignedUID 0x230
  World::ComponentsThatNeedPreEndOfFrameSync 0x238
  World::ComponentsThatNeedEndOfFrameUpdate 0x288
  World::ComponentsThatNeedEndOfFrameUpdate_OnGameThread 0x298
  World::WorldComposition 0x618
  World::PSCPool 0x6C8

  BuildingWeakSpot
  BuildingWeakSpot::ParentObject 0x248
  BuildingWeakSpot::bHit 0x250
  BuildingWeakSpot::bFadeOut 0x250
  BuildingWeakSpot::bActive 0x250
  BuildingWeakSpot::HitCount 0x254
  BuildingWeakSpot::Level 0x258
  BuildingWeakSpot::MaxLevel 0x25C
  BuildingWeakSpot::StartingLocation 0x260
  BuildingWeakSpot::HitNormal 0x26C
  BuildingWeakSpot::PhysicalSurfaceType 0x278

  FortPlayerControllerAthena
  FortPlayerControllerAthena::FireAbilityToWeaponSwitchTime 0x3430
  FortPlayerControllerAthena::OnAircraftStateChange 0x3440
  FortPlayerControllerAthena::OnItemDropSpawnedDelegate 0x3450
  FortPlayerControllerAthena::OnItemDroppedDueToOverflow 0x3460
  FortPlayerControllerAthena::OnCreativePermissionsChanged 0x3470
  FortPlayerControllerAthena::SwappingItemDefinition 0x3480
  FortPlayerControllerAthena::WinScreenDelayTime 0x3488
  FortPlayerControllerAthena::bSkipPlayWinEffects 0x348C
  FortPlayerControllerAthena::bAllowPlayersCreditOnLeave 0x348D
  FortPlayerControllerAthena::bLockingOnFocalPoint 0x348F
  FortPlayerControllerAthena::FocalPoint 0x3490
  FortPlayerControllerAthena::FocalPointOffset 0x3498
  FortPlayerControllerAthena::FocalPointFOV 0x34A4
  FortPlayerControllerAthena::FocalPointDuration 0x34A8
  FortPlayerControllerAthena::OnUsingFocalPointChanged 0x34B0
  FortPlayerControllerAthena::OnFocalPointActorChanged 0x34C0
  FortPlayerControllerAthena::OnSkydiveLeaderChanged 0x34D0
  FortPlayerControllerAthena::OnClientDonationSuccessDelegate 0x34E0
  FortPlayerControllerAthena::SkydiveLeaderManualCameraTime 0x351C
  FortPlayerControllerAthena::InterpolatedSkydiveFollowerViewRotation 0x3524
  FortPlayerControllerAthena::SkydiveLeader 0x3540
  FortPlayerControllerAthena::OnPickupProjectileCreatedDelegate 0x3550
  FortPlayerControllerAthena::LastDownedVictim 0x3560
  FortPlayerControllerAthena::LastElimVictim 0x3568
  FortPlayerControllerAthena::OnCameraInStormWallChangeDelegate 0x3578
  FortPlayerControllerAthena::bLeaveDisconnectedPawnsInGame 0x35A0
  FortPlayerControllerAthena::DisconnectedPawn 0x35A8
  FortPlayerControllerAthena::PreviousPawn 0x35B0
  FortPlayerControllerAthena::bReplicateViewTargetInventory 0x35B8
  FortPlayerControllerAthena::bHasHadValidPawn 0x35B9
  FortPlayerControllerAthena::bClientNotifiedOfWin 0x35B9
  FortPlayerControllerAthena::bClientNotifiedOfTeamWin 0x35B9
  FortPlayerControllerAthena::bClientNotifiedOfLoss 0x35B9
  FortPlayerControllerAthena::bHideWarmUpLoadingScreen 0x35B9
  FortPlayerControllerAthena::PlayersTalking 0x35E0
  FortPlayerControllerAthena::TalkingPlayersChanged 0x35F0
  FortPlayerControllerAthena::bHighlightRecordingEnabled 0x3600
  FortPlayerControllerAthena::bPlaceDangerMarkerWhenTargeting 0x3601
  FortPlayerControllerAthena::bDeferringStartRecordingHighlights 0x3602
  FortPlayerControllerAthena::HighlightGroupId 0x3608
  FortPlayerControllerAthena::CachedHighlightCount 0x3618
  FortPlayerControllerAthena::HighlightFirstKillTime 0x361C
  FortPlayerControllerAthena::HighlightKillMultiple 0x3620
  FortPlayerControllerAthena::HighlightDownMultiple 0x3624
  FortPlayerControllerAthena::HighlightKillCooldown 0x3628
  FortPlayerControllerAthena::HighlightKillRewindTime 0x362C
  FortPlayerControllerAthena::RespawnCamera_Time 0x3630
  FortPlayerControllerAthena::RespawnCamera_HoldPositionTime 0x3634
  FortPlayerControllerAthena::RespawnCamera_InitialLocOffset_InAir 0x3638
  FortPlayerControllerAthena::RespawnCamera_InitialLocOffset_OnGround 0x3644
  FortPlayerControllerAthena::RespawnCamera_InitialRotOffset_InAir 0x3650
  FortPlayerControllerAthena::RespawnCamera_InitialRotOffset_OnGround 0x365C
  FortPlayerControllerAthena::RespawnCamera_OffsetFromHit 0x3668
  FortPlayerControllerAthena::bNextRespawnInAir 0x366C
  FortPlayerControllerAthena::RespawnCameraBehavior 0x3670
  FortPlayerControllerAthena::MaximumNumberOfPawnsToSearchForEmoteMusic 0x36A0
  FortPlayerControllerAthena::PickupSwapHoldTime 0x36B0
  FortPlayerControllerAthena::bUseNewPickupSwapLogic 0x36B4
  FortPlayerControllerAthena::SpectatorLevelStreamDistance 0x36B8
  FortPlayerControllerAthena::RespawnLevelStreamDistance 0x36BC
  FortPlayerControllerAthena::SpectatorStreamingChanged 0x36C0
  FortPlayerControllerAthena::InGameLoadScreenChanged 0x36D0
  FortPlayerControllerAthena::OnLocalPlayerChangedTeams 0x36E0
  FortPlayerControllerAthena::LevelStreamRequestHandshakeState 0x3710
  FortPlayerControllerAthena::OnCreativePlotLinkedVolumeChanged 0x3748
  FortPlayerControllerAthena::OnClientLeaveIsland 0x3758
  FortPlayerControllerAthena::OnClientForcedOffIsland 0x3768
  FortPlayerControllerAthena::OnMakeNewCreativePlotFinished 0x3788
  FortPlayerControllerAthena::OnDestroyCreativePlotFinished 0x3798
  FortPlayerControllerAthena::OnRestoreCreativePlotFinished 0x37A8
  FortPlayerControllerAthena::OnDuplicateCreativePlotFinished 0x37B8
  FortPlayerControllerAthena::OnIslandEntriesChanged 0x37C8
  FortPlayerControllerAthena::OnUpdateCreativePlotName 0x37E8
  FortPlayerControllerAthena::OnUpdateCreativeDescriptionTags 0x37F8
  FortPlayerControllerAthena::RespawnCameraActor 0x3820
  FortPlayerControllerAthena::bDelayedTeleporting 0x3828
  FortPlayerControllerAthena::bBlockTeleporting 0x3829
  FortPlayerControllerAthena::MaxPlotCount 0x382C
  FortPlayerControllerAthena::InGameMatchmakingReadyCheckStarted 0x3890
  FortPlayerControllerAthena::InGameMatchmakingReadyCheckComplete 0x38A0
  FortPlayerControllerAthena::InGameMatchmakingReadyCheckCanceled 0x38B0
  FortPlayerControllerAthena::InGameMatchmakingStarted 0x38C0
  FortPlayerControllerAthena::InGameMatchmakingComplete 0x38D0
  FortPlayerControllerAthena::InGameMatchmakingStateChanged 0x38E0
  FortPlayerControllerAthena::InGameMatchmakingQueuedStatusUpdated 0x38F0
  FortPlayerControllerAthena::InGameMatchmakingError 0x3900
  FortPlayerControllerAthena::OnInGameMatchmakingCanceled 0x3910
  FortPlayerControllerAthena::OnInGameMatchmakingUpdateCheckFailed 0x3920
  FortPlayerControllerAthena::OnInGameContentDownloadStarted 0x3930
  FortPlayerControllerAthena::bNoInGameMatchmaking 0x3940
  FortPlayerControllerAthena::AudioOnExitAircraft 0x3970
  FortPlayerControllerAthena::AudioOnExitAircraftHornDoppler 0x3978
  FortPlayerControllerAthena::MinQuickChatCooldown 0x3980
  FortPlayerControllerAthena::QuickChatOffCooldownTime 0x3984
  FortPlayerControllerAthena::bMarkedAlive 0x3988
  FortPlayerControllerAthena::CreativeIslands 0x3990
  FortPlayerControllerAthena::LastUsedSavePlot 0x39A0
  FortPlayerControllerAthena::bIsAllowedToPublish 0x39B0
  FortPlayerControllerAthena::GamepadSettingsAssetPtr 0x39B8
  FortPlayerControllerAthena::TeamMemberIndicatorColor 0x39F8
  FortPlayerControllerAthena::bMatchStatsForPlayerSent 0x3A30
  FortPlayerControllerAthena::bAddedBookProgressStatsToGamemode 0x3A31
  FortPlayerControllerAthena::bHasSentMatchEndedQuestProgress 0x3A32
  FortPlayerControllerAthena::QuickBarDefinitions 0x3A38
  FortPlayerControllerAthena::bEnableBroadcastRemoteClientInfo 0x3A78
  FortPlayerControllerAthena::BroadcastRemoteClientInfo 0x3A80
  FortPlayerControllerAthena::StrongMyHero 0x3A90
  FortPlayerControllerAthena::ClientGameWorldHolds 0x3A98
  FortPlayerControllerAthena::EndMatchHeartbeatTimerDelay 0x3AD0
  FortPlayerControllerAthena::EndMatchHeartbeatTimestamp 0x3AD8
  FortPlayerControllerAthena::WarmupPlayerStart 0x3AE0
  FortPlayerControllerAthena::FullScreenScoreboardInputComponent 0x3AE8
  FortPlayerControllerAthena::CurrentFullscreenInputComponent 0x3AF0
  FortPlayerControllerAthena::GameChannelRecommendationInputComponent 0x3AF8
  FortPlayerControllerAthena::SocialNotificationInputComponent 0x3B00
  FortPlayerControllerAthena::bUseTrapPicker 0x3C75
  FortPlayerControllerAthena::DoubleTapEditTime 0x3CD8
  FortPlayerControllerAthena::MatchReport 0x3CE0
  FortPlayerControllerAthena::MinimapIndicatorClass 0x3CF8
  FortPlayerControllerAthena::MinimapChallengeIndicatorClass 0x3D00
  FortPlayerControllerAthena::MinimapChallengeIndicators 0x3D08
  FortPlayerControllerAthena::bEnableInGameChallengeLocationIndicators 0x3D10
  FortPlayerControllerAthena::SquadMarkerActorClass 0x3D18
  FortPlayerControllerAthena::BuildingsCreated 0x3D28
  FortPlayerControllerAthena::BuildingsEdited 0x3D2C
  FortPlayerControllerAthena::BuildingsRepaired 0x3D30
  FortPlayerControllerAthena::BuildingsUpgraded 0x3D34
  FortPlayerControllerAthena::BuildingActionDoneLastAtTime 0x3D38
  FortPlayerControllerAthena::BuildingMatchStats 0x3D3C
  FortPlayerControllerAthena::BuildingAnalyticsArray 0x3D60
  FortPlayerControllerAthena::TimeStartedTrackingBuildingAnalytics 0x3D70
  FortPlayerControllerAthena::CreativePlotLinkedVolume 0x3E50
  FortPlayerControllerAthena::CreativePlotSessionData 0x3E58
  FortPlayerControllerAthena::OwnedPortal 0x3E70
  FortPlayerControllerAthena::OwnedPartyRiftPortal 0x3E78
  FortPlayerControllerAthena::OnHUDMessageToggled 0x3EC8
  FortPlayerControllerAthena::CachedPurchasedItems 0x3ED8
  FortPlayerControllerAthena::CurrentPlayset 0x3F00
  FortPlayerControllerAthena::DestructedBuildingInGridTimeoutOverride 0x3F08
  FortPlayerControllerAthena::ClientRespawnText 0x3F10
  FortPlayerControllerAthena::ClientRebootingText 0x3F28
  FortPlayerControllerAthena::ClientIslandTravelText 0x3F40
  FortPlayerControllerAthena::ClientTravelToCreativeHubText 0x3F58
  FortPlayerControllerAthena::VolumesLoading 0x3F70
  FortPlayerControllerAthena::VolumesUnloading 0x3F80
  FortPlayerControllerAthena::MarkerComponent 0x3F90
  FortPlayerControllerAthena::ResurrectionComponent 0x3F98
  FortPlayerControllerAthena::SeasonItemComponent 0x3FA0
  FortPlayerControllerAthena::HeldDeviceUsageComponent 0x3FB0
  FortPlayerControllerAthena::XPComponent 0x3FD0
  FortPlayerControllerAthena::DiscoverabilityComponent 0x3FD8
  FortPlayerControllerAthena::TransientQuestsComponent 0x3FE0
  FortPlayerControllerAthena::SkydiveFeedback 0x3FE8
  FortPlayerControllerAthena::ContextualChallenges 0x3FF0
  FortPlayerControllerAthena::IndicatedActorManagementComponent 0x3FF8
  FortPlayerControllerAthena::LocalizationServiceComponent 0x4000
  FortPlayerControllerAthena::ToxicityServiceComponent 0x4008
  FortPlayerControllerAthena::RechargingWeaponsComponent 0x4010
  FortPlayerControllerAthena::InventoryServiceComponent 0x4018
  FortPlayerControllerAthena::RadiusTrackerComponent 0x4020
  FortPlayerControllerAthena::MinigameActivityComponent 0x4028
  FortPlayerControllerAthena::CreativeAnalyticsComponent 0x4030
  FortPlayerControllerAthena::SightWeatherCapRadius 0x4038
  FortPlayerControllerAthena::TimeSinceLastCreativeSpawn 0x4060
  FortPlayerControllerAthena::IgnoreSignifanceBasedCustomDepthRendering 0x4088
  FortPlayerControllerAthena::CreativeUserContentManager 0x40A0
  FortPlayerControllerAthena::CreativeUserContentManagerClassSoftClassPtr 0x40A8
  FortPlayerControllerAthena::CreativeObjectTrackingComponent 0x40E0
  FortPlayerControllerAthena::CreativeEntitlementComponent 0x40E8
  FortPlayerControllerAthena::OnPreviewScreenshotCameraActivated 0x40F0
  FortPlayerControllerAthena::CreativeItemToRemoveWhenAddingInventoryItem 0x41B8
  FortPlayerControllerAthena::PrimaryQuickBarSlotItemGuids 0x41E0
  FortPlayerControllerAthena::bIgnoreSpectatorViewRotation 0x42B0
  FortPlayerControllerAthena::bIgnorePlayerInfoAbandonStateForSpecialEventRtmm 0x42B1

  FortPlayerPawnAthena
 constexpr auto OnInteractionFailedCallback = 0x3c78; // FMulticastInlineDelegate
			constexpr auto ItemInteractionActor = 0x3c88; // AActor*
			constexpr auto CurrentPawnSquaredSpeed = 0x3ca0; // float
			constexpr auto CurrentPawnSquaredSpeedXY = 0x3ca4; // float
			constexpr auto CurrentPawnVelXYRot = 0x3ca8; // FRotator
			constexpr auto PreviousVelocityXY = 0x3cc0; // FVector
			constexpr auto OnReviveSound = 0x3cd8; // USoundBase*
			constexpr auto ReviveFromDBNOTime = 0x3ce0; // float
			constexpr auto DBNOStartTime = 0x3ce4; // float
			constexpr auto DBNOInvulnerableTime = 0x3ce8; // float
			constexpr auto ConvertFromDBNOTime = 0x3cec; // float
			constexpr auto ServerWorldTimeRevivalTime = 0x3cf0; // float
			constexpr auto bWasCrouchedBeforeDBNO = 0x3d00; // bool
			constexpr auto ItemSpecialActorID = 0x3d04; // FName
			constexpr auto ItemSpecialActorCategoryTag = 0x3d08; // FGameplayTag
			constexpr auto BecameSpecialActorTime = 0x3d10; // float
			constexpr auto OnUIGameplayCue = 0x3d18; // FMulticastInlineDelegate
			constexpr auto bPlaytestWithNoMouse = 0x3d28; // bool
			constexpr auto CapsuleRadiusAthena = 0x3d30; // float
			constexpr auto CapsuleHalfHeightAthena = 0x3d34; // float
			constexpr auto MeshHeightAdjustAthena = 0x3d38; // float
			constexpr auto LandEmitterTemplate = 0x3d40; // UParticleSystem*
			constexpr auto IgnoreLandGhostModeTags = 0x3d48; // FGameplayTagContainer
			constexpr auto LandWindEmitterTemplate = 0x3d68; // UParticleSystem*
			constexpr auto LandFXLocationOffset = 0x3d70; // FVector
			constexpr auto LandFXRotateYawMaxDegrees = 0x3d88; // float
			constexpr auto LandFXMaxDrawDistance = 0x3d8c; // float
			constexpr auto LandForceIntensityVelocityZFactor = 0x3d90; // float
			constexpr auto MinLandForceIntensity = 0x3d94; // float
			constexpr auto MaxLandForceIntensity = 0x3d98; // float
			constexpr auto MinLandForceDuration = 0x3d9c; // float
			constexpr auto MaxLandForceDuration = 0x3da0; // float
			constexpr auto LandFXCoolDownTime = 0x3da4; // float
			constexpr auto LandFXPawnRecentRenderTolerance = 0x3da8; // float
			constexpr auto bShouldPawnInstantDie = 0x3dc0; // bool
			constexpr auto bShouldPawnDBNODisplayOnKillFeed = 0x3dc1; // bool
			constexpr auto bShouldPawnDeathDisplayOnKillFeed = 0x3dc2; // bool
			constexpr auto bShouldPawnLeaveEliminationIndicator = 0x3dc3; // bool
			constexpr auto bShouldPawnAwardPoints = 0x3dc4; // bool
			constexpr auto bShouldTriggerDeathAnalytics = 0x3dc5; // bool
			constexpr auto bShouldDropItemsOnDeath = 0x3dc6; // bool
			constexpr auto bShouldSkipMovementFullSimulation = 0x3dc7; // bool
			constexpr auto bEnableRenderCustomDepth = 0x3dc8; // char : 1
			constexpr auto bEnableGroundInteractionEffects = 0x3dc8; // char : 1
			constexpr auto AttributeReplicationProxy = 0x3dcc; // FFortPlayerAthenaAttributeReplicationProxy
			constexpr auto GravityAttributeReplicationProxy = 0x3de4; // FFortPlayerAthenaGravityAttributeReplicationProxy
			constexpr auto ReplayRepAnimMontageInfo = 0x3df8; // FGameplayAbilityRepAnimMontage
			constexpr auto SimulatedProxyActiveGameplayCues = 0x3e30; // FMinimalGameplayCueReplicationProxy
			constexpr auto SimulatedProxyMinimalReplicationGameplayCues = 0x4100; // FMinimalGameplayCueReplicationProxy
			constexpr auto FastReplicationMinimalReplicationTags = 0x43d0; // FMinimalReplicationTagCountMap
			constexpr auto CurrentQuickChatIcon = 0x4438; // UTexture2D*
			constexpr auto bADSWhileNotOnGround = 0x4585; // bool
			constexpr auto DefaultCrouchedFootstepSound = 0x4588; // USoundBase*
			constexpr auto DefaultCrouchSprintFootstepSound = 0x4590; // USoundBase*
			constexpr auto OnFortPlayerDied = 0x4598; // FMulticastInlineDelegate
			constexpr auto OnFortPlayerHitByVehicle = 0x45a8; // FMulticastInlineDelegate
			constexpr auto KillerForSpectatorRotation = 0x45b8; // APawn*
			constexpr auto bDelaySimProxyCollisionInAircraftPhase = 0x45c1; // bool
			constexpr auto TimeToDelaySkydiveCollision = 0x45c4; // float
			constexpr auto PositionCaptureIntervalForDistanceTraveledAccumulation = 0x45c8; // float
			constexpr auto SkydiveAudioMovementVolumeInterpSpeed = 0x45e0; // float
			constexpr auto SkydiveAudioForwardDotInterpSpeed = 0x45f0; // float
			constexpr auto SkydiveAudioRightDotInterpSpeed = 0x45f4; // float
			constexpr auto DamageFXSignificance = 0x45fc; // FFortEffectDistanceQuality
			constexpr auto ScreenEffectHealthDamage = 0x4620; // AFortEmitterCameraLensEffectDirectional*
			constexpr auto ScreenEffectShieldDamage = 0x4628; // AFortEmitterCameraLensEffectDirectional*
			constexpr auto AdditiveHitReactsMontage = 0x4630; // UAnimMontage*
			constexpr auto DamageTagsToNotDisplayDirectionDamage = 0x4638; // FGameplayTagContainer
			constexpr auto DamageTagsToNotAddCameraShake = 0x4658; // FGameplayTagContainer
			constexpr auto WeaponTagsToNotPlayCircleAndStreakFX = 0x4678; // FGameplayTagContainer
			constexpr auto OnPlayerLootedContainer = 0x4698; // FMulticastInlineDelegate
			constexpr auto bIsPlayerPawnReady = 0x46c8; // bool
			constexpr auto LastFiredLocation = 0x46d0; // FVector
			constexpr auto LastFiredDirection = 0x46e8; // FVector
			constexpr auto LastFiredTime = 0x4700; // float
			constexpr auto PrototypeShootingModel = 0x4718; // UDataTable*
			constexpr auto FallInstigator = 0x4720; // AController*
			constexpr auto FallDamageTags = 0x4728; // FGameplayTagContainer
			constexpr auto LastFloorBeforeFalling = 0x4748; // ABuildingSMActor*
			constexpr auto LastFallDistance = 0x4750; // float
			constexpr auto SkydiveDebugTimer = 0x4754; // float
			constexpr auto MeleeCombatSlowSpeedMultiplier = 0x4758; // float
			constexpr auto MeleeCombatSlowDuration = 0x475c; // float
			constexpr auto EncryptedPawnReplayData = 0x4760; // FAthenaPawnReplayData
			constexpr auto InAirAudioComp = 0x4790; // UAudioComponent*
			constexpr auto PSC_PlayerWalkLand = 0x4798; // UParticleSystemComponent*
			constexpr auto PSC_PlayerRunLand = 0x47a0; // UParticleSystemComponent*
			constexpr auto PSC_PlayerSlideLand = 0x47a8; // UParticleSystemComponent*
			constexpr auto PSC_HitDamage = 0x47b0; // UParticleSystemComponent*
			constexpr auto SlidingAudioComp = 0x47b8; // UAudioComponent*
			constexpr auto MobileInteractionComponents = 0x47e0; // TArray<UFortMobileInteractionComponent*>
			constexpr auto MinimapIconColorFiftyFiftyPlayer = 0x47f0; // FLinearColor
			constexpr auto MaxIndicatorVisibilityDistForReplays = 0x4800; // float
			constexpr auto ConsumableUseAudio = 0x4808; // UAudioComponent*
			constexpr auto InAirAudioParameterValue = 0x4810; // float
			constexpr auto InAirAudioFallDistanceThreshold = 0x4814; // float
			constexpr auto bFXPlayDustOnMovement = 0x4819; // bool
			constexpr auto WalkDustActivateSpeed = 0x481c; // float
			constexpr auto WalkDustResetSpeed = 0x4824; // float
			constexpr auto RunParticleActivateSpeed = 0x482c; // float
			constexpr auto SlidingIntensitySound3P = 0x4840; // USoundBase*
			constexpr auto SlidingIntensitySound1P = 0x4848; // USoundBase*
			constexpr auto SlideAudioIntensity = 0x4850; // float
			constexpr auto LastHealthPostProcessWeight = 0x4854; // float
			constexpr auto HealthPostProcessStartTime = 0x4858; // float
			constexpr auto HealthPostProcessMuteTime = 0x485c; // float
			constexpr auto CustomDepthMatchedComponents = 0x48d0; // TArray<TWeakObjectPtr<UPrimitiveComponent>>
			constexpr auto bIsCreativeGhostModeActivated = 0x48e4; // bool
			constexpr auto bIsCreativeModeratorModeActivated = 0x48e5; // bool
			constexpr auto SkinWeightManager = 0x4910; // UFortSkinWeightOverrideManager*
			constexpr auto InvulnerabilityTags = 0x4950; // FGameplayTagContainer
			constexpr auto UnicornPawnSampler = 0x4970; // UUnicornAthenaPawnSampler*
			constexpr auto MarkerDisplay = 0x4978; // FMarkedActorDisplayInfo
			constexpr auto DamageForceFeedback = 0x4a20; // UForceFeedbackEffect*
			constexpr auto DamageCameraShakeClass = 0x4a28; // UMatineeCameraShake*
			constexpr auto DamageTagsExcludedFromCameraShake = 0x4a30; // FGameplayTagContainer
			constexpr auto UpdateSharedReplicationWhileAttachedCount = 0x4a68; // int32_t
			constexpr auto BP_RotationSpeedWhenTurnedOffByAnim = 0x4a6c; // float
			constexpr auto BP_RotationSpeedOnDetach = 0x4a70; // float
			constexpr auto BP_MaxRotationSpeedWhenAttached = 0x4a74; // float
			constexpr auto BP_TimeToReachMaxRotationSpeed = 0x4a78; // float
			constexpr auto BP_AddedRotationInfluenceFromForwardVectorOnAttach = 0x4a7c; // float
			constexpr auto YawNegative90 = 0x4a80; // FRotator
			constexpr auto CallerID_update_mesh_rotation = 0x4a98; // FString
			constexpr auto AttachPointNormalizeTolerance = 0x4aa8; // float
			constexpr auto ForwardProjectedNormalizeTolerance = 0x4aac; // float
			constexpr auto Swinging_AttachBGA = 0x4ab0; // ABuildingGameplayActor*
			constexpr auto Swinging_RightVec = 0x4ab8; // FVector
			constexpr auto Swinging_LastAttachTime = 0x4ad0; // float
			constexpr auto bSwingingShouldRotateMesh = 0x4ad4; // bool
			constexpr auto bSwinging_UseProgrammaticRotation = 0x4ad5; // bool
			constexpr auto bImprovedDBNOEnabled = 0x4ad6; // bool
			constexpr auto DBNORevivingActorsCount = 0x4ad7; // char

  FortPlayerPawnStats
  FortPlayerPawnStats::MaxJumpTime 0xB8
  FortPlayerPawnStats::MaxStamina 0xBC
  FortPlayerPawnStats::StaminaRegenRate 0xC0
  FortPlayerPawnStats::StaminaRegenDelay 0xC4
  FortPlayerPawnStats::SprintingStaminaExpenditureRate 0xC8
  FortPlayerPawnStats::PersonalVehicleFallingDamageTableRow 0xCC

  PlayerCameraManager
  PlayerCameraManager::PCOwner 0x220
  PlayerCameraManager::TransformComponent 0x228
  PlayerCameraManager::DefaultFOV 0x238
  PlayerCameraManager::DefaultOrthoWidth 0x240
  PlayerCameraManager::DefaultAspectRatio 0x248
  PlayerCameraManager::CameraCache 0x290
  PlayerCameraManager::LastFrameCameraCache 0x8E0
  PlayerCameraManager::ViewTarget 0xF30
  PlayerCameraManager::PendingViewTarget 0x1590
  PlayerCameraManager::CameraCachePrivate 0x1C20
  PlayerCameraManager::LastFrameCameraCachePrivate 0x2270
  PlayerCameraManager::ModifierList 0x28C0
  PlayerCameraManager::DefaultModifiers 0x28D0
  PlayerCameraManager::FreeCamDistance 0x28E0
  PlayerCameraManager::FreeCamOffset 0x28E4
  PlayerCameraManager::ViewTargetOffset 0x28F0
  PlayerCameraManager::OnAudioFadeChangeEvent 0x2900
  PlayerCameraManager::CameraLensEffects 0x2920
  PlayerCameraManager::CachedCameraShakeMod 0x2930
  PlayerCameraManager::AnimInstPool 0x2938
  PlayerCameraManager::PostProcessBlendCache 0x2978
  PlayerCameraManager::ActiveAnims 0x2998
  PlayerCameraManager::FreeAnims 0x29A8
  PlayerCameraManager::AnimCameraActor 0x29B8
  PlayerCameraManager::bIsOrthographic 0x29C0
  PlayerCameraManager::bDefaultConstrainAspectRatio 0x29C0
  PlayerCameraManager::bClientSimulatingViewTarget 0x29C0
  PlayerCameraManager::bUseClientSideCameraUpdates 0x29C0
  PlayerCameraManager::bGameCameraCutThisFrame 0x29C1
  PlayerCameraManager::ViewPitchMin 0x29C4
  PlayerCameraManager::ViewPitchMax 0x29C8
  PlayerCameraManager::ViewYawMin 0x29CC
  PlayerCameraManager::ViewYawMax 0x29D0
  PlayerCameraManager::ViewRollMin 0x29D4
  PlayerCameraManager::ViewRollMax 0x29D8
  PlayerCameraManager::ServerUpdateCameraTimeout 0x29E0

  FortProjectileAthena
  FortProjectileAthena::FireStartLoc 0x8C8
  FortProjectileAthena::PawnHitResult 0x8E0
  FortProjectileAthena::bExplodeOnPawnHit 0x97C
  FortProjectileAthena::bNoCollisionForNonOwningClients 0x97C
  FortProjectileAthena::bIgnoreActorsAttachedToFiringPawn 0x97C
  FortProjectileAthena::bProcessLocalHits 0x97C
  FortProjectileAthena::TimeToWaitForPawnHitBeforeKillOnServer 0x980
  FortProjectileAthena::PredictedHitActor 0x9D8
  FortProjectileAthena::PredictedHitComp 0x9E0

  FortPickup
  FortPickup::bUsePickupWidget 0x230
  FortPickup::bSuppressInteractionWidget 0x231
  FortPickup::bWeaponsCanBeAutoPickups 0x232
  FortPickup::bAutoUpgradeWeapons 0x233
  FortPickup::bDoServerHandlePickupTrace 0x234
  FortPickup::SimulatingTooLongLength 0x238
  FortPickup::OnPickup 0x240
  FortPickup::OnPickupAttempted 0x250
  FortPickup::OnPickupDespawned 0x260
  FortPickup::OnPickupDestroyed 0x270
  FortPickup::OnPickupCombined 0x280
  FortPickup::OnSetPawnWhoDroppedPickup 0x290
  FortPickup::PrimaryPickupItemEntry 0x2A8
  FortPickup::MultiItemPickupEntries 0x448
  FortPickup::PickupLocationData 0x458
  FortPickup::PickupSourceTypeFlags 0x4B8
  FortPickup::PickupSpawnSource 0x4B9
  FortPickup::OptionalOwnerID 0x4BA
  FortPickup::DropperID 0x4BC
  FortPickup::OptionalMissionGuid 0x4C0
  FortPickup::PrimaryPickupDummyItem 0x4D0
  FortPickup::PickupEffectBlueprint 0x4D8
  FortPickup::TouchCapsule 0x4E0
  FortPickup::MovementComponent 0x4E8
  FortPickup::WaterInteractionComponent 0x4F0
  FortPickup::LinkToActorComponent 0x4F8
  FortPickup::bPickedUp 0x500
  FortPickup::bSplitOnPickup 0x501
  FortPickup::bTossedFromContainer 0x502
  FortPickup::bForceHideMinimapIndicator 0x503
  FortPickup::bCombinePickupsWhenTossCompletes 0x504
  FortPickup::bServerStoppedSimulation 0x505
  FortPickup::bClientUseInterpolationOnly 0x506
  FortPickup::ServerImpactSoundFlash 0x507
  FortPickup::LastLandedSoundPlayTime 0x508
  FortPickup::OverrideInteractAimRadius 0x50C
  FortPickup::LandSoundZForceThreshold 0x510
  FortPickup::DefaultFlyTime 0x514
  FortPickup::bForceDefaultFlyTime 0x518
  FortPickup::DroppedLoopingSoundComp 0x520
  FortPickup::LandedSoundOverride 0x528
  FortPickup::PawnWhoDroppedPickup 0x530
  FortPickup::CachedSpecialActorIdx 0x538
  FortPickup::SpecialActorID 0x53C
  FortPickup::MinimapIndicator 0x548
  FortPickup::HUDLabel 0x550
  FortPickup::bRandomRotation 0x61C
  FortPickup::VolumeAtSpawn 0x620
  FortPickup::DespawnTime 0x640
  FortPickup::StormDespawnTime 0x644
  FortPickup::StartSimulatingTime 0x648

  FortPlayerStateAthena
  FortPlayerStateAthena::PersonalLobbyAction 0xDDC
  FortPlayerStateAthena::RespawnData 0xDE0
  FortPlayerStateAthena::ReplicatedTeamMemberState 0xE18
  FortPlayerStateAthena::TeamMemberState 0xE19
  FortPlayerStateAthena::TeamMemberStateRepTime 0xE1C
  FortPlayerStateAthena::OnTeamIndexChangedDelegate 0xE40
  FortPlayerStateAthena::OnSquadIdChangedDelegate 0xE50
  FortPlayerStateAthena::bHasWonAGame 0xEA8
  FortPlayerStateAthena::TeamKillScore 0xEAC
  FortPlayerStateAthena::KillsWhileAthenaGadgetEquippedMap 0xEB0
  FortPlayerStateAthena::DamageDealtToBigHealthProps 0xF00
  FortPlayerStateAthena::TeamIndex 0xF50
  FortPlayerStateAthena::TeamScorePlacement 0xF54
  FortPlayerStateAthena::TeamScore 0xF58
  FortPlayerStateAthena::Place 0xF5C
  FortPlayerStateAthena::DownScore 0xF60
  FortPlayerStateAthena::KillScore 0xF64
  FortPlayerStateAthena::SeasonLevelUIDisplay 0xF68
  FortPlayerStateAthena::HumanKillScore 0xF6C
  FortPlayerStateAthena::AIKillCount 0xFA8
  FortPlayerStateAthena::NumChestsOpened 0xFB0
  FortPlayerStateAthena::NumAmmoCansOpened 0xFB8
  FortPlayerStateAthena::NumSupplyDropsOpened 0xFC0
  FortPlayerStateAthena::NumLlamasOpened 0xFC8
  FortPlayerStateAthena::NumForagedItemsConsumed 0xFD0
  FortPlayerStateAthena::NumMinutesAlive 0xFD8
  FortPlayerStateAthena::NumBronzeCoinsCollected 0xFE0
  FortPlayerStateAthena::NumSilverCoinsCollected 0xFE8
  FortPlayerStateAthena::NumGoldCoinsCollected 0xFF0
  FortPlayerStateAthena::TotalPlayerScore 0xFF8
  FortPlayerStateAthena::PointsAddedToScore 0x1000
  FortPlayerStateAthena::TeamScoreChanged 0x1010
  FortPlayerStateAthena::TeamPlacementChanged 0x1020
  FortPlayerStateAthena::PlaceChanged 0x1030
  FortPlayerStateAthena::TeamAverageDamageChanged 0x1040
  FortPlayerStateAthena::MatchAbandonStateChanged 0x1050
  FortPlayerStateAthena::FriendsInSquad 0x1060
  FortPlayerStateAthena::FriendsInMatch 0x1070
  FortPlayerStateAthena::FriendsInSquadAtPartnerCafe 0x10C0
  FortPlayerStateAthena::StormSurgeEffectCount 0x1120
  FortPlayerStateAthena::TeamAverageDamageDealt 0x1122
  FortPlayerStateAthena::SquadId 0x1124
  FortPlayerStateAthena::bThankedBusDriver 0x1125
  FortPlayerStateAthena::bDidNotThankBusDriver 0x1125
  FortPlayerStateAthena::bUsingAnonymousMode 0x1125
  FortPlayerStateAthena::bUsingAnonymousCharacterMode 0x1125
  FortPlayerStateAthena::bShowingSeasonLevel 0x1125
  FortPlayerStateAthena::PlayerNameCustomOverride 0x1128
  FortPlayerStateAthena::bIsTalking 0x1140
  FortPlayerStateAthena::bIsMuted 0x1141
  FortPlayerStateAthena::OnInventoriesInNonPersistenceModeChanged 0x1340
  FortPlayerStateAthena::OnInventoriesInLocalOnlyModeChanged 0x1350
  FortPlayerStateAthena::MetricInformation 0x1380
  FortPlayerStateAthena::SimpleMetricInformation 0x1390
  FortPlayerStateAthena::SecondsAlive 0x13F0
  FortPlayerStateAthena::TimeOfPawnCreation 0x13F4
  FortPlayerStateAthena::bIsDisconnected 0x13FC
  FortPlayerStateAthena::GameModeIcon 0x1430
  FortPlayerStateAthena::DeathInfo 0x1438
  FortPlayerStateAthena::ChangeTeamInfo 0x14C8
  FortPlayerStateAthena::bResurrectionChipDisabled 0x1538
  FortPlayerStateAthena::ResurrectionChipAvailable 0x153C
  FortPlayerStateAthena::bResurrectingNow 0x1554
  FortPlayerStateAthena::RebootCounter 0x1558
  FortPlayerStateAthena::InteractingRebootVan 0x1560
  FortPlayerStateAthena::MatchAbandonState 0x156C
  FortPlayerStateAthena::bIsAnAthenaGameParticipant 0x156E
  FortPlayerStateAthena::bIsContributingToOverbudgetHeatmap 0x156E
  FortPlayerStateAthena::BotUniqueId 0x1570
  FortPlayerStateAthena::bPreserveSquad 0x1598
  FortPlayerStateAthena::KeepPlayingTogetherVotingStatus 0x15B8
  FortPlayerStateAthena::KeepPlayingTogetherMatchmakingRegion 0x15D8
  FortPlayerStateAthena::InitialSquadSize 0x1600
  FortPlayerStateAthena::SquadSizeIncrements 0x1601
  FortPlayerStateAthena::SquadSizeDecrements 0x1602
  FortPlayerStateAthena::bInventoriesInNonPersistenceMode 0x1650
  FortPlayerStateAthena::bInventoriesInLocalOnlyMode 0x1651

  FortItemEntry
  FortItemEntry::Count 0xC
  FortItemEntry::PreviousCount 0x10
  FortItemEntry::ItemDefinition 0x18
  FortItemEntry::OrderIndex 0x20
  FortItemEntry::Durability 0x24
  FortItemEntry::Level 0x28
  FortItemEntry::LoadedAmmo 0x2C
  FortItemEntry::PhantomReserveAmmo 0x30
  FortItemEntry::AlterationDefinitions 0x38
  FortItemEntry::SavedWeaponModSlots 0x48
  FortItemEntry::ItemSource 0x58
  FortItemEntry::ItemGuid 0x68
  FortItemEntry::TrackerGuid 0x78
  FortItemEntry::ItemVariantGuid 0x88
  FortItemEntry::ControlOverride 0x98
  FortItemEntry::inventory_overflow_date 0x9C
  FortItemEntry::bWasGifted 0x9D
  FortItemEntry::bIsReplicatedCopy 0x9E
  FortItemEntry::bIsDirty 0x9F
  FortItemEntry::bUpdateStatsOnCollection 0xA0
  FortItemEntry::GiftingInfo 0xA8
  FortItemEntry::StateValues 0xD0
  FortItemEntry::ParentInventory 0xE0
  FortItemEntry::GameplayAbilitySpecHandle 0xE8
  FortItemEntry::AlterationInstances 0xF0
  FortItemEntry::WeaponModSlots 0x100
  FortItemEntry::WrapOverride 0x110
  FortItemEntry::GenericAttributeValues 0x138
  FortItemEntry::PickupVariantIndex 0x198
  FortItemEntry::ItemVariantDataMappingIndex 0x19C

  ProceduralScatterActorContentVariation
  ProceduralScatterActorContentVariation::ActorClass 0x98

  FortWeaponItemDefinition
  FortWeaponItemDefinition::WeaponActorClass 0x840
  FortWeaponItemDefinition::WeaponMeshOverride 0x868
  FortWeaponItemDefinition::IntrinsicOverrideWrap 0x890
  FortWeaponItemDefinition::WeaponStatHandle 0x8B8
  FortWeaponItemDefinition::bRechargeAmmoToClip 0x8C8
  FortWeaponItemDefinition::WeaponRechargeAmmoRate 0x8D0
  FortWeaponItemDefinition::WeaponRechargeAmmoQuantity 0x8F8
  FortWeaponItemDefinition::AbilitySet 0x920
  FortWeaponItemDefinition::AlterationSlotsLoadoutRow 0x948
  FortWeaponItemDefinition::BaselineAlterationSlotsLoadoutRow 0x950
  FortWeaponItemDefinition::BaseAlteration 0x958
  FortWeaponItemDefinition::BaseCosmeticAlteration 0x980
  FortWeaponItemDefinition::WeaponModSlots 0x9A8
  FortWeaponItemDefinition::PrimaryFireAbility 0x9B8
  FortWeaponItemDefinition::SecondaryFireAbility 0x9E0
  FortWeaponItemDefinition::ReloadAbility 0xA08
  FortWeaponItemDefinition::OnHitAbility 0xA30
  FortWeaponItemDefinition::EquippedAbilities 0xA58
  FortWeaponItemDefinition::EquippedAbilitySet 0xA68
  FortWeaponItemDefinition::EquippedCharacterParts 0xA90
  FortWeaponItemDefinition::AmmoData 0xAA0
  FortWeaponItemDefinition::AdditionalDataFields 0xAC8
  FortWeaponItemDefinition::LowAmmoPercentage 0xAD8
  FortWeaponItemDefinition::TriggerType 0xADC
  FortWeaponItemDefinition::SecondaryTriggerType 0xADD
  FortWeaponItemDefinition::DisplayTier 0xADE
  FortWeaponItemDefinition::bUsesPhantomReserveAmmo 0xADF
  FortWeaponItemDefinition::bUsesCustomAmmoType 0xADF
  FortWeaponItemDefinition::bShouldMagazineSizeDisplayInfinity 0xADF
  FortWeaponItemDefinition::bAllowSecondaryFireToInterruptPrimary 0xADF
  FortWeaponItemDefinition::bAllowTargetingDuringReload 0xADF
  FortWeaponItemDefinition::bTargetingPreventsReload 0xADF
  FortWeaponItemDefinition::bCanFireWhileInstigatorTethered 0xADF
  FortWeaponItemDefinition::bCanFireWhileNotTargetedInVehicle 0xADF
  FortWeaponItemDefinition::bAlwaysChargeUpToMin 0xAE0
  FortWeaponItemDefinition::bNoFireOnReleaseBeforeMinChargeTime 0xAE0
  FortWeaponItemDefinition::bEndAbilityOnChargeEnd 0xAE0
  FortWeaponItemDefinition::bUpdateLastFireTimeOnDischarge 0xAE0
  FortWeaponItemDefinition::bReticleCornerOutsideSpreadRadius 0xAE0
  FortWeaponItemDefinition::bValidForLastEquipped 0xAE0
  FortWeaponItemDefinition::bRequestClientPreload 0xAE0
  FortWeaponItemDefinition::bEnableWeaponMeshOverrideUpdates 0xAE0
  FortWeaponItemDefinition::HitNotifyDuration 0xAE4
  FortWeaponItemDefinition::ReticleImage 0xAE8
  FortWeaponItemDefinition::ReticleCornerAngles 0xB10
  FortWeaponItemDefinition::ReticleCenterImage 0xB20
  FortWeaponItemDefinition::ReticleCenterPerfectAimImage 0xB48
  FortWeaponItemDefinition::ReticleCenterImageOffset 0xB70
  FortWeaponItemDefinition::ReticleInvalidTargetImage 0xB78
  FortWeaponItemDefinition::AnalyticTags 0xBA0
  FortWeaponItemDefinition::PlayerGrantedGameplayTags 0xBC0
  FortWeaponItemDefinition::ActualAnalyticFNames 0xBE0
  FortWeaponItemDefinition::RequiredWeaponParent 0xBF0
  FortWeaponItemDefinition::CreativeTagsHelper 0xC18
  FortWeaponItemDefinition::AdditionalData 0xC28

  FortBaseWeaponStats
  FortBaseWeaponStats::BaseLevel 0xC
  FortBaseWeaponStats::NamedWeightRow 0x10
  FortBaseWeaponStats::DmgPB 0x18
  FortBaseWeaponStats::DmgMid 0x1C
  FortBaseWeaponStats::DmgLong 0x20
  FortBaseWeaponStats::DmgMaxRange 0x24
  FortBaseWeaponStats::EnvDmgPB 0x28
  FortBaseWeaponStats::EnvDmgMid 0x2C
  FortBaseWeaponStats::EnvDmgLong 0x30
  FortBaseWeaponStats::EnvDmgMaxRange 0x34
  FortBaseWeaponStats::ImpactDmgPB 0x38
  FortBaseWeaponStats::ImpactDmgMid 0x3C
  FortBaseWeaponStats::ImpactDmgLong 0x40
  FortBaseWeaponStats::ImpactDmgMaxRange 0x44
  FortBaseWeaponStats::bForceControl 0x48
  FortBaseWeaponStats::RngPB 0x4C
  FortBaseWeaponStats::RngMid 0x50
  FortBaseWeaponStats::RngLong 0x54
  FortBaseWeaponStats::RngMax 0x58
  FortBaseWeaponStats::DmgScaleTable 0x60
  FortBaseWeaponStats::DmgScaleTableRow 0x68
  FortBaseWeaponStats::DmgScale 0x70
  FortBaseWeaponStats::EnvDmgScaleTable 0x78
  FortBaseWeaponStats::EnvDmgScaleTableRow 0x80
  FortBaseWeaponStats::EnvDmgScale 0x88
  FortBaseWeaponStats::ImpactDmgScaleTable 0x90
  FortBaseWeaponStats::ImpactDmgScaleTableRow 0x98
  FortBaseWeaponStats::ImpactDmgScale 0xA0
  FortBaseWeaponStats::SurfaceRatioRowName 0xA4
  FortBaseWeaponStats::DamageZone_Light 0xAC
  FortBaseWeaponStats::DamageZone_Normal 0xB0
  FortBaseWeaponStats::DamageZone_Critical 0xB4
  FortBaseWeaponStats::DamageZone_Vulnerability 0xB8
  FortBaseWeaponStats::KnockbackMagnitude 0xBC
  FortBaseWeaponStats::MidRangeKnockbackMagnitude 0xC0
  FortBaseWeaponStats::LongRangeKnockbackMagnitude 0xC4
  FortBaseWeaponStats::KnockbackZAngle 0xC8
  FortBaseWeaponStats::ShortRangeHitImpulseMagnitude 0xCC
  FortBaseWeaponStats::MidRangeHitImpulseMagnitude 0xD0
  FortBaseWeaponStats::LongRangeHitImpulseMagnitude 0xD4
  FortBaseWeaponStats::HitImpulseZBias 0xD8
  FortBaseWeaponStats::StunTime 0xDC
  FortBaseWeaponStats::StunScale 0xE0
  FortBaseWeaponStats::Durability 0xE8
  FortBaseWeaponStats::DurabilityRowName 0xF0
  FortBaseWeaponStats::DurabilityScale 0xF8
  FortBaseWeaponStats::DurabilityPerUse 0xFC
  FortBaseWeaponStats::FullChargeDurabilityPerUse 0x100
  FortBaseWeaponStats::DiceCritChance 0x104
  FortBaseWeaponStats::DiceCritDamageMultiplier 0x108
  FortBaseWeaponStats::ReloadTime 0x10C
  FortBaseWeaponStats::ReloadScale 0x110
  FortBaseWeaponStats::ReloadType 0x114
  FortBaseWeaponStats::bAllowReloadInterrupt 0x115
  FortBaseWeaponStats::bReloadInterruptIsImmediate 0x116
  FortBaseWeaponStats::NumIndividualBulletsToReload 0x118
  FortBaseWeaponStats::ClipSize 0x11C
  FortBaseWeaponStats::ClipScale 0x120
  FortBaseWeaponStats::InitialClips 0x124
  FortBaseWeaponStats::CartridgePerFire 0x128
  FortBaseWeaponStats::AmmoCostPerFire 0x12C
  FortBaseWeaponStats::MaxAmmoCostPerFire 0x130
  FortBaseWeaponStats::MinChargeTime 0x134
  FortBaseWeaponStats::MaxChargeTime 0x138
  FortBaseWeaponStats::ChargeDownTime 0x13C
  FortBaseWeaponStats::bAutoDischarge 0x140
  FortBaseWeaponStats::MaxChargeTimeUntilDischarge 0x144
  FortBaseWeaponStats::MinChargeDamageMultiplier 0x148
  FortBaseWeaponStats::MaxChargeDamageMultiplier 0x14C
  FortBaseWeaponStats::ChargeDamageMultiplierCurve 0x150
  FortBaseWeaponStats::EquipAnimRate 0x158
  FortBaseWeaponStats::QuickBarSlotCooldownDuration 0x15C

  FortRangedWeaponStats
  FortRangedWeaponStats::Spread 0x16C
  FortRangedWeaponStats::OverrideBaseSpread 0x170
  FortRangedWeaponStats::SpreadDownsights 0x174
  FortRangedWeaponStats::StandingStillSpreadMultiplier 0x178
  FortRangedWeaponStats::AthenaCrouchingSpreadMultiplier 0x17C
  FortRangedWeaponStats::AthenaSlidingSpreadMultiplier 0x180
  FortRangedWeaponStats::AthenaJumpingFallingSpreadMultiplier 0x184
  FortRangedWeaponStats::AthenaSprintingSpreadMultiplier 0x188
  FortRangedWeaponStats::MinSpeedForSpreadMultiplier 0x18C
  FortRangedWeaponStats::MaxSpeedForSpreadMultiplier 0x190
  FortRangedWeaponStats::SpreadDownsightsAdditionalCooldownTime 0x194
  FortRangedWeaponStats::SpreadExponent 0x198
  FortRangedWeaponStats::HeatX1 0x19C
  FortRangedWeaponStats::HeatY1 0x1A0
  FortRangedWeaponStats::HeatX2 0x1A4
  FortRangedWeaponStats::HeatY2 0x1A8
  FortRangedWeaponStats::HeatX3 0x1AC
  FortRangedWeaponStats::HeatY3 0x1B0
  FortRangedWeaponStats::HeatXScale 0x1B4
  FortRangedWeaponStats::HeatYScale 0x1B8
  FortRangedWeaponStats::CoolX1 0x1BC
  FortRangedWeaponStats::CoolY1 0x1C0
  FortRangedWeaponStats::CoolX2 0x1C4
  FortRangedWeaponStats::CoolY2 0x1C8
  FortRangedWeaponStats::CoolX3 0x1CC
  FortRangedWeaponStats::CoolY3 0x1D0
  FortRangedWeaponStats::CoolXScale 0x1D4
  FortRangedWeaponStats::CoolYScale 0x1D8
  FortRangedWeaponStats::PerfectAimCooldown 0x1DC
  FortRangedWeaponStats::BulletsPerCartridge 0x1E0
  FortRangedWeaponStats::FiringRate 0x1E4
  FortRangedWeaponStats::ROFScale 0x1E8
  FortRangedWeaponStats::BurstFiringRate 0x1EC
  FortRangedWeaponStats::FiringRateDownsightsMultiplier 0x1F0
  FortRangedWeaponStats::AutofireRange 0x1F4
  FortRangedWeaponStats::AutofireAcquisitionDelay 0x1F8
  FortRangedWeaponStats::AutofireDBNOAcquisitionDelay 0x1FC
  FortRangedWeaponStats::AutofireAcquisitionRechargeTime 0x200
  FortRangedWeaponStats::AutofireReleaseTime 0x204
  FortRangedWeaponStats::AutofireCooldown 0x208
  FortRangedWeaponStats::RecoilVert 0x20C
  FortRangedWeaponStats::RecoilVertScale 0x210
  FortRangedWeaponStats::RecoilVertScaleGamepad 0x214
  FortRangedWeaponStats::VertRecoilDownChance 0x218
  FortRangedWeaponStats::RecoilHoriz 0x21C
  FortRangedWeaponStats::RecoilHorizScale 0x220
  FortRangedWeaponStats::RecoilHorizScaleGamepad 0x224
  FortRangedWeaponStats::RecoilInterpSpeed 0x228
  FortRangedWeaponStats::RecoilRecoveryInterpSpeed 0x22C
  FortRangedWeaponStats::RecoilRecoveryDelay 0x230
  FortRangedWeaponStats::RecoilRecoveryFraction 0x234
  FortRangedWeaponStats::RecoilDownsightsMultiplier 0x238
  FortRangedWeaponStats::AthenaRecoilMagnitudeMin 0x23C
  FortRangedWeaponStats::AthenaRecoilMagnitudeMax 0x240
  FortRangedWeaponStats::AthenaRecoilMagnitudeScale 0x244
  FortRangedWeaponStats::AthenaRecoilAngleMin 0x248
  FortRangedWeaponStats::AthenaRecoilAngleMax 0x24C
  FortRangedWeaponStats::AthenaRecoilRollMagnitudeMin 0x250
  FortRangedWeaponStats::AthenaRecoilRollMagnitudeMax 0x254
  FortRangedWeaponStats::AthenaRecoilInterpSpeed 0x258
  FortRangedWeaponStats::AthenaRecoilRecoveryInterpSpeed 0x25C
  FortRangedWeaponStats::AthenaRecoilDownsightsMultiplier 0x260
  FortRangedWeaponStats::AthenaRecoilHipFireMultiplier 0x264
  FortRangedWeaponStats::PitchLimitForPerBulletRecoil 0x268
  FortRangedWeaponStats::AthenaAimAssistRange 0x26C
  FortRangedWeaponStats::ADSTransitionInTime 0x270
  FortRangedWeaponStats::ADSTransitionOutTime 0x274
  FortRangedWeaponStats::MaxSpareAmmo 0x278
  FortRangedWeaponStats::BulletsPerTracer 0x27C
  FortRangedWeaponStats::AIDelayBeforeFiringMin 0x280
  FortRangedWeaponStats::AIDelayBeforeFiringMax 0x284
  FortRangedWeaponStats::AIFireDurationMin 0x288
  FortRangedWeaponStats::AIFireDurationMax 0x28C
  FortRangedWeaponStats::AIMinSpreadDuration 0x290
  FortRangedWeaponStats::AIMaxSpreadDuration 0x294
  FortRangedWeaponStats::AIDurationSpreadMultiplier 0x298
  FortRangedWeaponStats::AIAdditionalSpreadForTargetMovingLaterally 0x29C
  FortRangedWeaponStats::AIAthenaHearFiringNoiseRange 0x2A0
  FortRangedWeaponStats::EQSDensity 0x2A4
  FortRangedWeaponStats::MinApproachRange 0x2A8
  FortRangedWeaponStats::MinActualRange 0x2AC
  FortRangedWeaponStats::MinPreferredRange 0x2B0
  FortRangedWeaponStats::MinPreferredRangeEQS 0x2B4
  FortRangedWeaponStats::MaxPreferredRangeEQS 0x2B8
  FortRangedWeaponStats::MaxPreferredRange 0x2BC
  FortRangedWeaponStats::MaxActualRange 0x2C0
  FortRangedWeaponStats::MaxApproachRange 0x2C4
  FortRangedWeaponStats::RangeToAutomaticallyAddEnemyPawnGoals 0x2C8
  FortRangedWeaponStats::SweepRadius 0x2CC
  FortRangedWeaponStats::AutoReloadDelayOverride 0x2D0
  FortRangedWeaponStats::OverheatingMaxValue 0x2D4
  FortRangedWeaponStats::OverheatHeatingValue 0x2D8
  FortRangedWeaponStats::FullChargeOverheatHeatingValue 0x2DC
  FortRangedWeaponStats::OverheatingCoolingValue 0x2E0
  FortRangedWeaponStats::FullyOverheatedCoolingValue 0x2E4
  FortRangedWeaponStats::HeatingCooldownDelay 0x2E8
  FortRangedWeaponStats::OverheatedCooldownDelay 0x2EC
  FortRangedWeaponStats::bCoolOverheatWhileCharging 0x2F0
  FortRangedWeaponStats::FortHomingTurnSpeedMin 0x2F4
  FortRangedWeaponStats::FortHomingTurnSpeedMax 0x2F8
  FortRangedWeaponStats::FortHomingTimeUntilMaxTurnSpeed 0x2FC
  FortRangedWeaponStats::AimAssistPullStrengthMultiplier 0x300
  FortRangedWeaponStats::AimAssistSlowStrengthMultiplier 0x304
  FortRangedWeaponStats::BulletsPerBulletFireFX 0x308
  FortRangedWeaponStats::PerBulletRecoil 0x310

  FortPlayerStateZone
  FortPlayerStateZone::OnCurrentPawnChanged 0xA48
  FortPlayerStateZone::SpectatingTarget 0xA70
  FortPlayerStateZone::Spectators 0xA78
  FortPlayerStateZone::OnSpectatorsRemovedEvent 0xBA8
  FortPlayerStateZone::OnSpectatorCountChangedEvent 0xBB8
  FortPlayerStateZone::OnSpectatingTargetChangedEvent 0xBC8
  FortPlayerStateZone::OnBeginSpectatingEvent 0xBD8
  FortPlayerStateZone::KickedFromSessionReason 0xBF0
  FortPlayerStateZone::RS_Zone_Old 0xBF4
  FortPlayerStateZone::CarriedObject 0xD10
  FortPlayerStateZone::NumRejoins 0xD18
  FortPlayerStateZone::OldTotalScoreStat 0xD1C
  FortPlayerStateZone::bInvincibleDueToUI 0xD38
  FortPlayerStateZone::CurrentHealth 0xD3C
  FortPlayerStateZone::MaxHealth 0xD40
  FortPlayerStateZone::CurrentShield 0xD44
  FortPlayerStateZone::MaxShield 0xD48
  FortPlayerStateZone::CurrentOvershield 0xD4C
  FortPlayerStateZone::MaxOvershield 0xD50
  FortPlayerStateZone::CurrentSignalInStorm 0xD54
  FortPlayerStateZone::MaxSignalInStorm 0xD58
  FortPlayerStateZone::bOvershieldBarVisible 0xD5C
  FortPlayerStateZone::OnOvershieldVisibilityChanged 0xD60
  FortPlayerStateZone::AccumulatedItems 0xD78
  FortPlayerStateZone::OnAccumulatedItemsChanged 0xD88
  FortPlayerStateZone::SimulatedAttributes 0xD98
  FortPlayerStateZone::PendingDestroyedGadgetItemDefinition 0xDA8
  FortPlayerStateZone::bInAircraft 0xDB0
  FortPlayerStateZone::bHasEverSkydivedFromBus 0xDB0
  FortPlayerStateZone::bHasEverSkydivedFromBusAndLanded 0xDB0
  FortPlayerStateZone::QuickbarEquippedItems 0xDB8

  FortPlaylist
  FortPlaylist::PlaylistId 0x30
  FortPlaylist::PlaylistName 0x34
  FortPlaylist::GameType 0x3C
  FortPlaylist::MinPlayers 0x40
  FortPlaylist::MaxPlayers 0x44
  FortPlaylist::bUnderfillMatchmaking 0x48
  FortPlaylist::UnderfilledMaxPlayers 0x4C
  FortPlaylist::bOverrideMaxPlayers 0x50
  FortPlaylist::MaxHumanAndBotParticipants 0x54
  FortPlaylist::MaxTeamCount 0x58
  FortPlaylist::MaxTeamSize 0x5C
  FortPlaylist::MaxSocialPartySize 0x60
  FortPlaylist::MaxSquadSize 0x64
  FortPlaylist::MaxSquads 0x68
  FortPlaylist::EnforceSquadFill 0x6C
  FortPlaylist::bAllowSquadFillOption 0x6D
  FortPlaylist::bShouldFillWhenNoSquadFillOption 0x6E
  FortPlaylist::bAllowJoinInProgress 0x6F
  FortPlaylist::JoinInProgressMatchType 0x70
  FortPlaylist::EndOfMatchXpFirstElim 0x88
  FortPlaylist::EndOfMatchXpMultiplier 0x8C
  FortPlaylist::UserOptions 0x90
  FortPlaylist::bEnableBackfillDuringWarmupPhase 0x98
  FortPlaylist::TimeAfterWarmupToDisableBackfill 0x9C
  FortPlaylist::RichPresenceAssetName 0xA0
  FortPlaylist::bAllowKeepPlayingTogether 0xA8
  FortPlaylist::bAllowPartyRift 0xA9
  FortPlaylist::bAllowSquadSizeTracking 0xAA
  FortPlaylist::PreloadPersistentLevel 0xB0
  FortPlaylist::AdditionalLevels 0xD8
  FortPlaylist::AdditionalLevelsServerOnly 0xE8
  FortPlaylist::BuiltInGameFeaturePluginsToLoad 0xF8
  FortPlaylist::OverrideGameFeaturePluginToDownload 0x108
  FortPlaylist::GameFeaturePluginToActivateUntilDownloadedContentIsPresent 0x118
  FortPlaylist::DefaultFirstTeam 0x128
  FortPlaylist::DefaultLastTeam 0x129
  FortPlaylist::GameplayTagContainer 0x130
  FortPlaylist::FriendlyFireType 0x150
  FortPlaylist::bUseFriendlyFireAimAssist 0x151
  FortPlaylist::LootLevel 0x154
  FortPlaylist::LootTagQuery 0x158
  FortPlaylist::BuildingLevelOverride 0x1A0
  FortPlaylist::DBNOType 0x1A4
  FortPlaylist::SpawnImmunityTime 0x1A8
  FortPlaylist::SkippedGamePhaseNotification 0x1D0
  FortPlaylist::ModifierList 0x1E0
  FortPlaylist::TimeOfDayManager 0x1F0
  FortPlaylist::bIgnoreWeatherEvents 0x218
  FortPlaylist::ItemsToFullyLoad 0x220
  FortPlaylist::SharedAssetGroup 0x230
  FortPlaylist::ConditionalAssetGroup 0x238
  FortPlaylist::bIsDefaultPlaylist 0x240
  FortPlaylist::UIDisplayName 0x248
  FortPlaylist::UIDescription 0x260
  FortPlaylist::HUDElementsToHide 0x278
  FortPlaylist::LootTierData 0x298
  FortPlaylist::LootPackages 0x2C0
  FortPlaylist::BaseCurveTableOverrides 0x2E8
  FortPlaylist::BaseDataTablesOverride 0x2F8
  FortPlaylist::RangedWeapons 0x308
  FortPlaylist::GameData 0x330
  FortPlaylist::ResourceRates 0x358
  FortPlaylist::SkydiveMusic 0x380
  FortPlaylist::SkydiveMusicOutroStinger 0x3A8
  FortPlaylist::RespawnStinger 0x3D0
  FortPlaylist::GarbageCollectionFrequency 0x3F8
  FortPlaylist::ServerPerformanceEventFrequency 0x3FC
  FortPlaylist::ServerMetricsEventFrequency 0x400
  FortPlaylist::bUseLocalizationService 0x404

  FortPlaylistAthena
  FortPlaylistAthena::bRewardsTrackPlacement 0x408
  FortPlaylistAthena::bRewardsAllowXPProgression 0x409
  FortPlaylistAthena::bRewardForRevivingTeammates 0x40A
  FortPlaylistAthena::RewardPlacementBonusType 0x40B
  FortPlaylistAthena::RewardsPlacementThreshold 0x40C
  FortPlaylistAthena::RewardTimePlayedType 0x410
  FortPlaylistAthena::RewardTimePlayedXPPerMinute 0x414
  FortPlaylistAthena::RewardTimePlayedXPFlatValue 0x418
  FortPlaylistAthena::InMatchXPRewardScalar 0x420
  FortPlaylistAthena::QuestEventXPTableOverride 0x448
  FortPlaylistAthena::FirstWinRewards 0x470
  FortPlaylistAthena::CalendarEventsForEndOfMatchUpdate 0x480
  FortPlaylistAthena::bAllowSinglePartyMatches 0x490
  FortPlaylistAthena::bRequeueAfterFailedSessionAssignment 0x491
  FortPlaylistAthena::bIsTournament 0x492
  FortPlaylistAthena::bUseMultidivisionQueues 0x493
  FortPlaylistAthena::CompetitivePointClamp 0x494
  FortPlaylistAthena::Strategy 0x498
  FortPlaylistAthena::BotVersionPlaylistName 0x4A8
  FortPlaylistAthena::MaxBucketCapacity 0x4B0
  FortPlaylistAthena::MaxPendingMatches 0x4B4
  FortPlaylistAthena::PriorityRatingExpansion 0x4B8
  FortPlaylistAthena::bUseInputRules 0x4C8
  FortPlaylistAthena::bAllowBackfill 0x4C9
  FortPlaylistAthena::MinBackfillMatchPlayers 0x4CC
  FortPlaylistAthena::MaxTeamScoreAllowedForBackfill 0x4D0
  FortPlaylistAthena::MinPlayersForPrivateServer 0x4D4
  FortPlaylistAthena::MaxTeamScoreDiscrepancyPercent 0x4D8
  FortPlaylistAthena::bUsePlayerRating 0x4DC
  FortPlaylistAthena::bEnableRatingUpdate 0x4DD
  FortPlaylistAthena::bEnableDynamicBotBackfill 0x4DE
  FortPlaylistAthena::RatingType 0x4E0
  FortPlaylistAthena::bRequireCrossplayEnabled 0x4F0
  FortPlaylistAthena::bLimitedPoolMatchmakingEnabled 0x4F1
  FortPlaylistAthena::bAllowedInLeto 0x4F2
  FortPlaylistAthena::LastQueuedPlaylistPriority 0x4F4
  FortPlaylistAthena::bAllowInGameMatchMaking 0x4F8
  FortPlaylistAthena::bAllowReturnToMatchmakingOriginOnMatchEnd 0x4F9
  FortPlaylistAthena::bAllowBotsInHumanTeams 0x4FA
  FortPlaylistAthena::bForceNewPlayerStateOnReconnect 0x4FB
  FortPlaylistAthena::bShouldErrorOnAdditionalContentFailure 0x4FC
  FortPlaylistAthena::bRemoveFromSquadOnLogout 0x4FD
  FortPlaylistAthena::DADTestValue 0x500
  FortPlaylistAthena::RequiredCatalogItemId 0x508
  FortPlaylistAthena::DelayForPreServerTransitionAnimation 0x518
  FortPlaylistAthena::WinConditionType 0x51C
  FortPlaylistAthena::TimedWinConditionTime 0x520
  FortPlaylistAthena::FinalWinConditionTime 0x548
  FortPlaylistAthena::ScoringData 0x570
  FortPlaylistAthena::TimedSafeZonePhaseTime 0x5D0
  FortPlaylistAthena::WinConditionPlayersRemaining 0x5F8
  FortPlaylistAthena::NumWinningTeamsCN 0x600
  FortPlaylistAthena::bIsLargeTeamGame 0x628
  FortPlaylistAthena::bShouldSpreadTeams 0x629
  FortPlaylistAthena::bIgnoreDefaultQuests 0x62A
  FortPlaylistAthena::bDisallowMultipleWeaponsOfType 0x62B
  FortPlaylistAthena::bAllowEditingEnemyWalls 0x62C
  FortPlaylistAthena::LootDropRounds 0x630
  FortPlaylistAthena::ForceKickAfterDeathTime 0x634
  FortPlaylistAthena::ForceKickAfterDeathMode 0x638
  FortPlaylistAthena::QuickbarSelectionPreservationMode 0x639
  FortPlaylistAthena::AlwaysAllowedNativeActions 0x640
  FortPlaylistAthena::PawnForcedCullDistance 0x660
  FortPlaylistAthena::TransientMatchStartBonusCurrency 0x688
  FortPlaylistAthena::InventoryItemsToGrant 0x6B0
  FortPlaylistAthena::bIgnoreGameModeStartingInventory 0x6C0
  FortPlaylistAthena::bRequirePickaxeInStartingInventory 0x6C1
  FortPlaylistAthena::DestructedBuildingInGridTimeout 0x6C4
  FortPlaylistAthena::bTeamFilterDestructedBuildingsInGrid 0x6C8
  FortPlaylistAthena::bOwnerFilterDestructedBuildingsInGrid 0x6C9
  FortPlaylistAthena::bEnableBuildingCreatedEvent 0x6CA
  FortPlaylistAthena::MaximumAspectRatio 0x6CC
  FortPlaylistAthena::bVehiclesDestroyAllBuildingSMActorsOnContact 0x6D0
  FortPlaylistAthena::VehicleBoundsXYSplineClass 0x6D8
  FortPlaylistAthena::bAutoAcquireSpawnChip 0x6E0
  FortPlaylistAthena::SoundMix 0x6E8
  FortPlaylistAthena::bAllowHardcoreModifiers 0x6F0
  FortPlaylistAthena::bForceCameraFadeOnRespawn 0x6F1
  FortPlaylistAthena::MinTimeBeforeRespawnCameraFade 0x6F4
  FortPlaylistAthena::RespawnType 0x6F8
  FortPlaylistAthena::RespawnHeight 0x700
  FortPlaylistAthena::MaxRespawnHeight 0x728
  FortPlaylistAthena::RespawnTime 0x750
  FortPlaylistAthena::bRespawnInAir 0x778
  FortPlaylistAthena::RespawnLevelStreamDistanceToForceScreenFade 0x780
  FortPlaylistAthena::bForceRespawnLocationInsideOfVolume 0x7A8
  FortPlaylistAthena::bSkipWarmup 0x7A9
  FortPlaylistAthena::bSkipAircraft 0x7AA
  FortPlaylistAthena::bAllowWarmupPlayerStartInSetupPhase 0x7AB
  FortPlaylistAthena::WarmupEarlyRequiredPlayerPercent 0x7AC
  FortPlaylistAthena::AirCraftBehavior 0x7B0
  FortPlaylistAthena::bUseCustomAircraftPathSelection 0x7B1
  FortPlaylistAthena::bUseSameDirectionForOpposingAircraft 0x7B2
  FortPlaylistAthena::bAircraftDropOnlyWithinSafeZone 0x7B3
  FortPlaylistAthena::AircraftSafetyMarginPct 0x7B8
  FortPlaylistAthena::AircraftPathOffsetFromMapCenterMin 0x7E0
  FortPlaylistAthena::AircraftPathOffsetFromMapCenterMax 0x7E4
  FortPlaylistAthena::AircraftPathMidpointSelectionRadiusMin 0x7E8
  FortPlaylistAthena::AircraftPathMidpointSelectionRadiusMax 0x7EC
  FortPlaylistAthena::LastStepPushAircraftCenterLine_Magnitude 0x7F0
  FortPlaylistAthena::LastStepPushAircraftCenterLine_Direction 0x7F4
  FortPlaylistAthena::bDisableAudioShapes 0x7F8
  FortPlaylistAthena::NonRenderedCharacterAnimationScale 0x7FC
  FortPlaylistAthena::PlaylistMissionGen 0x800
  FortPlaylistAthena::bForceLTMLoadingScreenBackground 0x808
  FortPlaylistAthena::LoadingScreenWidget 0x810
  FortPlaylistAthena::UIExtensions 0x838
  FortPlaylistAthena::PlaylistUIData 0x848
  FortPlaylistAthena::HUDInfoDataAsset 0x870
  FortPlaylistAthena::MissionIcon 0x898
  FortPlaylistAthena::UIDisplaySubName 0x8A0
  FortPlaylistAthena::bLimitedTimeMode 0x8B8
  FortPlaylistAthena::bDisable_ReportAPlayerReason_TeamingUpWithEnemies_WhileInGame 0x8B9
  FortPlaylistAthena::bDisplayScoreInHUD 0x8BA
  FortPlaylistAthena::bDisplayRespawnWidget 0x8BB
  FortPlaylistAthena::bDisableMatchStatsDisplay 0x8BC
  FortPlaylistAthena::SpecialActorInputActionDataTableRow 0x8C0
  FortPlaylistAthena::bEnforceFullSquadInUI 0x8D0
  FortPlaylistAthena::bShowEliminationIndicatorForSelf 0x8D1
  FortPlaylistAthena::bShowEliminationIndicatorForSquadmates 0x8D2
  FortPlaylistAthena::bShowEliminationIndicatorForTeammates 0x8D3
  FortPlaylistAthena::bShowEliminationIndicatorForEnemies 0x8D4
  FortPlaylistAthena::EliminationIndicatorMaxDistance 0x8D8
  FortPlaylistAthena::bLeaderboardDisplaysIndividuals 0x900
  FortPlaylistAthena::bUsePointLeaderAsTeamLeaderInLeaderboard 0x901
  FortPlaylistAthena::TypeOfLeaderboard 0x902
  FortPlaylistAthena::OnlyRespectsGlobalSettingForReplayRecording 0x908
  FortPlaylistAthena::DisableReplays 0x930
  FortPlaylistAthena::EnableServerReplays 0x958
  FortPlaylistAthena::ShouldUseCustomGameChannel 0x980
  FortPlaylistAthena::ShouldRejectDefaultGameChat 0x9A8
  FortPlaylistAthena::CustomGameChannel 0x9D0
  FortPlaylistAthena::ShouldRecommendCustomGameChannel 0x9D8
  FortPlaylistAthena::bForceGameChannel 0xA00
  FortPlaylistAthena::MapImageOverride 0xA10
  FortPlaylistAthena::MapScaleOverride 0xAC0
  FortPlaylistAthena::bDrawCreativeDynamicIslands 0xAC4
  FortPlaylistAthena::MapManagerClass 0xAC8
  FortPlaylistAthena::bUseAsyncPhysics 0xAF0
  FortPlaylistAthena::ServerMaxTickRate 0xAF1
  FortPlaylistAthena::bOverrideServerPerClientMaxAI 0xAF2
  FortPlaylistAthena::ServerPerClientMaxAI 0xAF4
  FortPlaylistAthena::SafeZoneStartUp 0xAF8
  FortPlaylistAthena::bWarmUpInStorm 0xAF9
  FortPlaylistAthena::StormEffectDelay 0xAFC
  FortPlaylistAthena::bDisplayFinalStormPosition 0xB00
  FortPlaylistAthena::bDrawLineToStormCircleIfOutside 0xB01
  FortPlaylistAthena::LastSafeZoneIndex 0xB04
  FortPlaylistAthena::SafeZoneLocationBlacklist 0xB08
  FortPlaylistAthena::CreativeItemListSource 0xB30
  FortPlaylistAthena::UpgradeBenchData 0xB58
  FortPlaylistAthena::AILootOnDeathData 0xB80
  FortPlaylistAthena::HeroStats 0xBA8
  FortPlaylistAthena::bUseDefaultSupplyDrops 0xBD0
  FortPlaylistAthena::SupplyDropModifierList 0xBD8
  FortPlaylistAthena::SupplyDropInfoList 0xBE8
  FortPlaylistAthena::QueryNameToLootChanceScaleTables 0xBF8
  FortPlaylistAthena::QueryNameToLootCountScaleTables 0xC08
  FortPlaylistAthena::ExitCraftInfo 0xC18
  FortPlaylistAthena::bPlaylistUsesCustomCharacterParts 0xC40
  FortPlaylistAthena::CharactersToPreload 0xC48
  FortPlaylistAthena::CharacterFallbackTagsToPreload 0xC58
  FortPlaylistAthena::AIPawnCustomizationFallbackTagsToPreload 0xC68
  FortPlaylistAthena::SpawnActorInfoList 0xC78
  FortPlaylistAthena::NetActorDiscoveryBudgetInKBytesPerSec 0xC88
  FortPlaylistAthena::NetDormancyNumFramesUntilObsolete 0xC8C
  FortPlaylistAthena::bEnableCreativeMode 0xC90
  FortPlaylistAthena::bEnableSpawningStartup 0xC90
  FortPlaylistAthena::bAllowTeamSwitching 0xC90
  FortPlaylistAthena::bShowTeamSelectButton 0xC90
  FortPlaylistAthena::bAllowLayoutRequirementsFeature 0xC90
  FortPlaylistAthena::bUseCreativeStarterIsland 0xC90
  FortPlaylistAthena::bForceCustomMinigame 0xC90
  FortPlaylistAthena::bPreloadAthenaMapsForMatchmaking 0xC90
  FortPlaylistAthena::bUsesAnimationSharing 0xC91
  FortPlaylistAthena::AnimationSharingSetup 0xC98
  FortPlaylistAthena::bAllowBroadcasting 0xCC0
  FortPlaylistAthena::bAllowSpectateAPartyMember 0xCC1
  FortPlaylistAthena::bActivateCurie 0xCC2
  FortPlaylistAthena::CurieSettings 0xCC8
  FortPlaylistAthena::CurieManagerConfigOverrides 0xCD0
  FortPlaylistAthena::PlaylistStatId 0xCE0
  FortPlaylistAthena::bAccumulateToProfileStats 0xCE4
  FortPlaylistAthena::bSaveToRecentGameList 0xCE5
  FortPlaylistAthena::bEnableStatsV2Stats 0xCE6
  FortPlaylistAthena::AISettings 0xCE8
  FortPlaylistAthena::DefaultCreativeTOD 0xCF0
  FortPlaylistAthena::MaxVehiclesCanSpawnWithTireMod 0xD18
  FortPlaylistAthena::PercentChanceSpawnWithTireMod 0xD40

  FortProjectileMovementComponent
  FortProjectileMovementComponent::HomingData 0x1D0
  FortProjectileMovementComponent::InitialHomingStyle 0x20C
  FortProjectileMovementComponent::bHasHomedTowardTarget 0x20D
  FortProjectileMovementComponent::bSetInitialLocAndDir 0x20E
  FortProjectileMovementComponent::bReplicatedAutoRegisterUpdatedComponent 0x20F
  FortProjectileMovementComponent::bReplicateStopSimulating 0x20F
  FortProjectileMovementComponent::HomingLaserTargetDistance 0x210
  FortProjectileMovementComponent::HomingTravelTime 0x214
  FortProjectileMovementComponent::LockedOnTarget 0x218
  FortProjectileMovementComponent::DesiredDirection 0x220
  FortProjectileMovementComponent::PreviousHomingTargetPosition 0x22C
  FortProjectileMovementComponent::LaunchPosition 0x238
  FortProjectileMovementComponent::InitialDirection 0x244
  FortProjectileMovementComponent::AccelerationMagnitude 0x250
  FortProjectileMovementComponent::ReplicatedVelocityData 0x254
  FortProjectileMovementComponent::FortStopSimulatingRepData 0x264
  FortProjectileMovementComponent::WaterInteractionComponent 0x278
  FortProjectileMovementComponent::OnProjectileVelocityReplicated 0x290
  FortProjectileMovementComponent::bUseSeparateGravityScaleInWater 0x2D8
  FortProjectileMovementComponent::GravityScaleInWater 0x2DC

  K2_TeleportTo
  K2_TeleportTo::DestRotation 0xC
  K2_TeleportTo::ReturnValue 0x18

  K2_SetActorRotation
  K2_SetActorRotation::bTeleportPhysics 0xC
  K2_SetActorRotation::ReturnValue 0xD

  K2_SetActorLocationAndRotation
  K2_SetActorLocationAndRotation::NewRotation 0xC
  K2_SetActorLocationAndRotation::bSweep 0x18
  K2_SetActorLocationAndRotation::SweepHitResult 0x1C
  K2_SetActorLocationAndRotation::bTeleport 0xB8
  K2_SetActorLocationAndRotation::ReturnValue 0xB9

  K2_SetActorRelativeLocation
  K2_SetActorRelativeLocation::bSweep 0xC
  K2_SetActorRelativeLocation::SweepHitResult 0x10
  K2_SetActorRelativeLocation::bTeleport 0xAC

  K2_SetActorRelativeRotation
  K2_SetActorRelativeRotation::bSweep 0xC
  K2_SetActorRelativeRotation::SweepHitResult 0x10
  K2_SetActorRelativeRotation::bTeleport 0xAC

  K2_SetActorRelativeTransform
  K2_SetActorRelativeTransform::bSweep 0x30
  K2_SetActorRelativeTransform::SweepHitResult 0x34
  K2_SetActorRelativeTransform::bTeleport 0xD0

  K2_AttachToComponent
  K2_AttachToComponent::SocketName 0x8
  K2_AttachToComponent::LocationRule 0x10
  K2_AttachToComponent::RotationRule 0x11
  K2_AttachToComponent::ScaleRule 0x12
  K2_AttachToComponent::bWeldSimulatedBodies 0x13

  FortRuntimeOptions
  FortRuntimeOptions::CreativePlaysetPropActorPaths 0x38
  FortRuntimeOptions::bCanAccoladesDeviceGrantAccolades 0x48
  FortRuntimeOptions::CreativeBetaPermissions 0x50
  FortRuntimeOptions::bEnableItemDefinitionWhiteListing 0x60
  FortRuntimeOptions::bEnableItemDefinitionWhiteListingForTransientPickups 0x61
  FortRuntimeOptions::bAlwaysReadyUpAllLocalPlayersForMatchmaking 0x62
  FortRuntimeOptions::IslandResources 0x68
  FortRuntimeOptions::VolumeManagerBannedClasses 0x78
  FortRuntimeOptions::CreativeIslandDescriptionTagsMaxQty 0x88
  FortRuntimeOptions::CreativeIslandDescriptionTagsWhitelist 0x90
  FortRuntimeOptions::ExperimentalCohortPercent 0xA0
  FortRuntimeOptions::ExperimentalBucketPercentList 0xB0
  FortRuntimeOptions::bEnableSpectatorUpdates 0xC0
  FortRuntimeOptions::bIsTournamentMode 0xC1
  FortRuntimeOptions::bIsOutOfSeasonMode 0xC2
  FortRuntimeOptions::bForceBRMode 0xC3
  FortRuntimeOptions::bLoadDirectlyIntoLobby 0xC4
  FortRuntimeOptions::bAllowBPTokenRefund 0xC5
  FortRuntimeOptions::bEnableSpeculativeCreativeMMTeamSizeFix 0xC6
  FortRuntimeOptions::bUseTournamentAnonymousOverrideEnabled 0xC7
  FortRuntimeOptions::bForceDisallowAnonymousMode 0xC8
  FortRuntimeOptions::bEnableGeneratedScreenshotForPortalPreview 0xC9
  FortRuntimeOptions::bAllowLoadoutSwitchingInLobby 0xCA
  FortRuntimeOptions::IngameMatchmakingDelaySeconds 0xCC
  FortRuntimeOptions::NumSavedLoadouts 0xD0
  FortRuntimeOptions::TournamentPlaylistName 0xD4
  FortRuntimeOptions::TournamentPlaylistPriorityBase 0xDC
  FortRuntimeOptions::TournamentModeQueueInterval 0xE0
  FortRuntimeOptions::MinimumAccountLevelForTournamentPlay 0xE4
  FortRuntimeOptions::bEnableManualBroadcasterStart 0xE8
  FortRuntimeOptions::bForcePRM 0xE9
  FortRuntimeOptions::bCreativeManualBroadcasterStart 0xEA
  FortRuntimeOptions::bCreativeEnableTimerForPhoneToolEnforcement 0xEB
  FortRuntimeOptions::bAutoloadRestrictedPlots 0xEC
  FortRuntimeOptions::bDisableMyIslandDescriptionPanel 0xED
  FortRuntimeOptions::bEnableAllRemoteClientInfos 0xEE
  FortRuntimeOptions::bEnableBuildPreviewForBroadcast 0xEF
  FortRuntimeOptions::bEnableRemoteAimSnapshotManagerForBroadcast 0xF0
  FortRuntimeOptions::EsportsAnalyticsHeartbeatRate 0xF4
  FortRuntimeOptions::bUseBroadcastPostProcessing 0xF8
  FortRuntimeOptions::bUseBroadcastKillFeed 0xF9
  FortRuntimeOptions::bUseServerReplayActionFeed 0xFA
  FortRuntimeOptions::bReplayGoToTimeEnabled 0xFB
  FortRuntimeOptions::bBroadcastPipModeToggle 0xFC
  FortRuntimeOptions::bShowBroadcastPlayerEventScoreWidget 0xFD
  FortRuntimeOptions::bUseOutsideTopThreeSpectatorLeaderboard 0xFE
  FortRuntimeOptions::bReplayPauseZeroDeltas 0xFF
  FortRuntimeOptions::CurrentSocialImportVersion 0x100
  FortRuntimeOptions::PawnDeathScreenDelay 0x104
  FortRuntimeOptions::CurrentVKImportVersion 0x108
  FortRuntimeOptions::bEnableMassFriendImport 0x10C
  FortRuntimeOptions::bEnableSocialTab 0x10D
  FortRuntimeOptions::bAllowSocialPresenceUpdates 0x10E
  FortRuntimeOptions::bEnableToastSocialWidget 0x10F
  FortRuntimeOptions::bEnableINICachedSocialStatus 0x110
  FortRuntimeOptions::MaxINICachedSocialStatuses 0x114
  FortRuntimeOptions::MinSecondsBetweenINICachedSocialStatuses 0x118
  FortRuntimeOptions::NumDaysBeforeFailedImportReattempt 0x120
  FortRuntimeOptions::bEnableSocialBanModal 0x124
  FortRuntimeOptions::bEnableDedicatedServerSocialBanVoiceQuery 0x125
  FortRuntimeOptions::bEnableDedicatedServerSocialBanVoiceEnforcement 0x126
  FortRuntimeOptions::bDisplayLastOnlineTime 0x127
  FortRuntimeOptions::bDisplayLastInteraction 0x128
  FortRuntimeOptions::bEnableStartupSocialImport 0x129
  FortRuntimeOptions::bEnableBladeRAF 0x12A
  FortRuntimeOptions::bEnableStartupErebusFriendImport 0x12B
  FortRuntimeOptions::bEnableVKImport 0x12C
  FortRuntimeOptions::bEnableSteamImport 0x12D
  FortRuntimeOptions::SocialImportURI 0x130
  FortRuntimeOptions::DaysBetweenSocialImportPrompts 0x140
  FortRuntimeOptions::DaysBetweenVKImportPrompt 0x144
  FortRuntimeOptions::FriendImportCaptionSelection 0x148
  FortRuntimeOptions::bEnableSplitWalletTextNotice 0x14C
  FortRuntimeOptions::bShowAthenaStoreToast 0x14D
  FortRuntimeOptions::bShowAthenaStoreToastForRolloverAlone 0x14E
  FortRuntimeOptions::bAllow3DInspectOfRMTItems 0x14F
  FortRuntimeOptions::bAltUpdateFlow 0x150
  FortRuntimeOptions::bShowRMTDescriptionPopup 0x151
  FortRuntimeOptions::bAllowJuniorEndingMovie 0x152
  FortRuntimeOptions::AthenaStarterGameMode 0x158
  FortRuntimeOptions::AthenaStarterFill 0x168
  FortRuntimeOptions::PartyRichPresenceUpdateTime 0x16C
  FortRuntimeOptions::PartySuggestionUpdateTimer 0x170
  FortRuntimeOptions::MaxPartySuggestionsToConsider 0x174
  FortRuntimeOptions::bAllowLFG 0x178
  FortRuntimeOptions::bAllowPartyPresenceUpdates 0x179
  FortRuntimeOptions::bAllowGameplayPresenceUpdates 0x17A
  FortRuntimeOptions::bEnablePlaylistNameInRichPresence 0x17B
  FortRuntimeOptions::bAllowDiscordFrictionlessJoin 0x17C
  FortRuntimeOptions::bEnableInteractiveConsumables 0x17D
  FortRuntimeOptions::bEnableContextHelpMenu 0x17E
  FortRuntimeOptions::bShowAthenaItemShop 0x17F
  FortRuntimeOptions::bEnableShowdown 0x180
  FortRuntimeOptions::bEnableTournamentMatchCaps 0x181
  FortRuntimeOptions::bUsePlayingEventIds 0x182
  FortRuntimeOptions::bRetryCMSLoads 0x183
  FortRuntimeOptions::RefreshScoreDelay 0x184
  FortRuntimeOptions::bAlwaysForceTournamentLobbyPanelRefresh 0x188
  FortRuntimeOptions::bEnableEventLeaderboards 0x189
  FortRuntimeOptions::NumCachedLeaderboardPages 0x18C
  FortRuntimeOptions::MaxPagesPerLeaderboard 0x190
  FortRuntimeOptions::EventLeaderboardLiveRefreshTimeSeconds 0x194
  FortRuntimeOptions::EventLeaderboardLivePostEventRefreshWindowMinutes 0x198
  FortRuntimeOptions::bGetLiveSessionsFromLeaderboards 0x19C
  FortRuntimeOptions::bUseServerTournamentPlacementNotifications 0x19D
  FortRuntimeOptions::MaximumEventLengthHoursForCallout 0x1A0
  FortRuntimeOptions::bEnableHypeLeaderboards 0x1A4
  FortRuntimeOptions::bEnableSwapRegionsButton 0x1A5
  FortRuntimeOptions::bFillCompetitivePanelFromDiscovery 0x1A6
  FortRuntimeOptions::HypeLeaderboardEventId 0x1A8
  FortRuntimeOptions::HypeLeaderboardRefreshTimeSeconds 0x1B8
  FortRuntimeOptions::bHypeLeaderboardIncludeFriendsTab 0x1BC
  FortRuntimeOptions::CreativePlaylistName 0x1C0
  FortRuntimeOptions::BattleLabPlaylistName 0x1C8
  FortRuntimeOptions::CampaignPlaylistName 0x1D0
  FortRuntimeOptions::bEnableEventScoreClamping 0x1D8
  FortRuntimeOptions::CreativeDisabledTabIndex 0x1DC
  FortRuntimeOptions::bAllowIslandExporting 0x1E0
  FortRuntimeOptions::bAllowCreativeModeratorMode 0x1E1
  FortRuntimeOptions::bIslandExportingEnabledMCPOverride 0x1E2
  FortRuntimeOptions::bEnableCreativeServerImportFriendsOption 0x1E3
  FortRuntimeOptions::MaxPlayersInCreativeServer 0x1E4
  FortRuntimeOptions::MaxPlayersInCreativeWhitelist 0x1E8
  FortRuntimeOptions::bShowSupportACreatorOnIslandLinkScreen 0x1EC
  FortRuntimeOptions::bHideServersWithZeroPlayers 0x1ED
  FortRuntimeOptions::bEnableIslandCodeEntryOnPlayerPortal 0x1EE
  FortRuntimeOptions::bEnableIslandCodeEntryOnCuratedPortal 0x1EF
  FortRuntimeOptions::bEnableIslandCodeEntryInFrontend 0x1F0
  FortRuntimeOptions::RefreshFavoriteIslandsWaitTime 0x1F4
  FortRuntimeOptions::IslandCodeLength 0x1F8
  FortRuntimeOptions::bApplyCodeFormatting 0x1FC
  FortRuntimeOptions::bAdvertiseBattleLabOwnerInSession 0x1FD
  FortRuntimeOptions::bEnableThermometerUIForBattleLab 0x1FE
  FortRuntimeOptions::bEnableSpatialThermometerForBattleLab 0x1FF
  FortRuntimeOptions::bEnableHeatmapUIDisplayForCreative 0x200
  FortRuntimeOptions::bEnableHeatmapUIDisplayForBattleLab 0x201
  FortRuntimeOptions::bUseHeatmapHighPrecison 0x202
  FortRuntimeOptions::bEnableBudgetTrackerSpatialTest 0x203
  FortRuntimeOptions::bEnableSpatialThermometerForCreative 0x204
  FortRuntimeOptions::bEnableSpatialSettingsForCreative 0x205
  FortRuntimeOptions::bIsMatchmakingEnabledForPlayers 0x206
  FortRuntimeOptions::CreativeHeatmapThermometerCellSize 0x208
  FortRuntimeOptions::bEnableThermomterCostPreviwer 0x20C
  FortRuntimeOptions::bEnableSlateVersionOfThermometer 0x20D
  FortRuntimeOptions::bEnableJoinInProgress 0x20E
  FortRuntimeOptions::bEnableSpectateAPartyMember 0x20F
  FortRuntimeOptions::bEnableJoinAndSpectate 0x210
  FortRuntimeOptions::bEnableRequestToJoin 0x211
  FortRuntimeOptions::MaxNumAlivePlayersForSpectateAPartyMember 0x214
  FortRuntimeOptions::MaxNumPartyMemberSpectatorsPerMatch 0x218
  FortRuntimeOptions::SpectateAPartyMemberPlaylistOverrides 0x220
  FortRuntimeOptions::bEnableJoinInProgressInMatchmakingWidget 0x230
  FortRuntimeOptions::bAnyPartyMemberAllowedToCancelMatchmakingV2 0x231
  FortRuntimeOptions::bEnableLockerSearch 0x232
  FortRuntimeOptions::bEnableLockerDirtySearch 0x233
  FortRuntimeOptions::bEnableBattlePass 0x234
  FortRuntimeOptions::bEnableBattlePassFAQ 0x235
  FortRuntimeOptions::bShowBattlePassBangAfterPurchase 0x236
  FortRuntimeOptions::bShowBattlePassBangEveryLevel 0x237
  FortRuntimeOptions::bShowBattlePassBangs 0x238
  FortRuntimeOptions::bSkipBattlePassPurchaseTextScreen 0x239
  FortRuntimeOptions::bBattlePassPurchaseSound 0x23A
  FortRuntimeOptions::bBattlePassPurchaseDialog 0x23B
  FortRuntimeOptions::bBattlePassFTUEFix 0x23C
  FortRuntimeOptions::bBattlePassVideoDelay 0x23D
  FortRuntimeOptions::bEnableAthenaFavoriting 0x23E
  FortRuntimeOptions::bShowAthenaDailyQuests 0x23F
  FortRuntimeOptions::bShowAthenaDailyQuestsWithAllChallenges 0x240
  FortRuntimeOptions::bEnableAthenaCustomPreviewActionForCosmetics 0x241
  FortRuntimeOptions::bEnableAthenaItemRandomization 0x242
  FortRuntimeOptions::bEnableProfileStatTracking 0x243
  FortRuntimeOptions::bEnableProfileStatUI 0x244
  FortRuntimeOptions::bEnableTrickUI 0x245
  FortRuntimeOptions::bEnableMultiplayerTricks 0x246
  FortRuntimeOptions::bShowAthenaChallengesTabWhenOutOfSeason 0x247
  FortRuntimeOptions::bEnableInGameChallengeTree 0x248
  FortRuntimeOptions::bCreateEpicAccountPinGrantDisabled 0x249
  FortRuntimeOptions::bLoginEpicWeb 0x24A
  FortRuntimeOptions::bLoginXBLDisabled 0x24B
  FortRuntimeOptions::bLoginPSNDisabled 0x24C
  FortRuntimeOptions::bLoginErebusDisabled 0x24D
  FortRuntimeOptions::bSkipInternetCheck 0x24E
  FortRuntimeOptions::bEnableClientSettingsSaveToCloud 0x24F
  FortRuntimeOptions::bEnableClientSettingsSaveToDisk 0x250
  FortRuntimeOptions::bEnableClientSettingsRestoreInputPresets 0x251
  FortRuntimeOptions::bDedServerEventServiceDownloadTryCount 0x254
  FortRuntimeOptions::TournamentRefreshPayoutMaxRateSeconds 0x258
  FortRuntimeOptions::TournamentRefreshEventsMaxRateSeconds 0x25C
  FortRuntimeOptions::TournamentRefreshPlayerMaxRateSeconds 0x260
  FortRuntimeOptions::TournamentHUDPointCounterDelay 0x264
  FortRuntimeOptions::MaxNumDisplayNamesOnLiveGameList 0x268
  FortRuntimeOptions::LiveGameListInitialLimit 0x26C
  FortRuntimeOptions::LiveGameListQueryIncreaseAmount 0x270
  FortRuntimeOptions::bEnableLiveGamesScreen 0x274
  FortRuntimeOptions::bLiveGameTimeDurationVisible 0x275
  FortRuntimeOptions::bEnableFlagSelection 0x276
  FortRuntimeOptions::DefaultFlagRegionId 0x278
  FortRuntimeOptions::MixedNationTeamFlagRegionId 0x288
  FortRuntimeOptions::DisabledFlagSelections 0x298
  FortRuntimeOptions::FlagChangeCooldownDays 0x2A8
  FortRuntimeOptions::bEnableEventServicePayouts 0x2AC
  FortRuntimeOptions::bLiveGamesClientAnalyticsEnabled 0x2AD
  FortRuntimeOptions::MinimumWaitTimeToRequestNewShowdownScoreForWindow 0x2B0
  FortRuntimeOptions::EventServicePayoutRefreshRateSeconds 0x2B4
  FortRuntimeOptions::EventServicePayoutRefreshSpreadSeconds 0x2B8
  FortRuntimeOptions::BundleLoaderWidgetTimerInterval 0x2BC
  FortRuntimeOptions::CancelledEvents 0x2C0
  FortRuntimeOptions::SecondsShowStartingMatchMessageForScheduledMMEvents 0x2D0
  FortRuntimeOptions::bEnableMatchAbandonProcess 0x2D4
  FortRuntimeOptions::MatchAbandonTimeout 0x2D8
  FortRuntimeOptions::bEnableMultidivisionTournamentEventIdQuorum 0x2DC
  FortRuntimeOptions::CloudSaveIntervalConfig 0x2E0
  FortRuntimeOptions::bSaveToCloudOnMapLoad 0x2E8
  FortRuntimeOptions::bSaveToCloudOnSuspend 0x2E9
  FortRuntimeOptions::bSaveToCloudOnDeactivate 0x2EA
  FortRuntimeOptions::bSaveToCloudOnTerminate 0x2EB
  FortRuntimeOptions::bSaveToCloudOnExit 0x2EC
  FortRuntimeOptions::bSaveToCloudOnLogout 0x2ED
  FortRuntimeOptions::GiftNotificationRefreshTimer 0x2F0
  FortRuntimeOptions::bEnableUndoPurchase 0x2F8
  FortRuntimeOptions::bMoveUndoToBottomBar 0x2F9
  FortRuntimeOptions::bShowStoreBanner 0x2FA
  FortRuntimeOptions::InGameStoreUpdateChance 0x2FC
  FortRuntimeOptions::bEnableReplayBrowser 0x300
  FortRuntimeOptions::WhitelistedReplayCLs 0x308
  FortRuntimeOptions::bAllowAllReplays 0x318
  FortRuntimeOptions::bEnableReplayRecording 0x319
  FortRuntimeOptions::bEnableLargeTeamReplayRecording 0x31A
  FortRuntimeOptions::bEnableCreativeModeReplayRecording 0x31B
  FortRuntimeOptions::bEnablePlaygroundModeReplayRecording 0x31C
  FortRuntimeOptions::bEnableSplitscreenReplayRecording 0x31D
  FortRuntimeOptions::bEnableReplayDemoSplitting 0x31E
  FortRuntimeOptions::bStableReplayPlayback 0x31F
  FortRuntimeOptions::bEnableHearingAccessibility 0x320
  FortRuntimeOptions::bDisableSpatializationInsteadOfMutingWhenHearingAccessibilityEnabled 0x321
  FortRuntimeOptions::bAllowVisualizingSoundsWithStereoAudio 0x322
  FortRuntimeOptions::bEnableMetaSoundTestSimple 0x323
  FortRuntimeOptions::bEnableMetaSoundTestComplex 0x324
  FortRuntimeOptions::bDisableGiftXMPPMessageSend 0x325
  FortRuntimeOptions::bDisableGifting 0x326
  FortRuntimeOptions::bEnableGiftEligibilityCheck 0x327
  FortRuntimeOptions::bImmediateClaimOfEmote 0x328
  FortRuntimeOptions::bForceRestrictChat 0x329
  FortRuntimeOptions::bLimitGiftingToEligiblePlatforms 0x32A
  FortRuntimeOptions::bCanGiftYourself 0x32B
  FortRuntimeOptions::GiftLimitAmount 0x32C
  FortRuntimeOptions::bBattlePassGiftingEmergencyDisable 0x330
  FortRuntimeOptions::bEnableBattlePassGiftingButton 0x331
  FortRuntimeOptions::bEnableBattlePassGiftingButtonTokenOnly 0x332
  FortRuntimeOptions::bShowBPGiftBoxPopup 0x333
  FortRuntimeOptions::EndBattleRoyalUpdateDelay 0x334
  FortRuntimeOptions::LightswitchDownLoginDelay 0x338
  FortRuntimeOptions::bShowStatusButtonOnWaitingRoomScreen 0x33C
  FortRuntimeOptions::bInvertMotionOnUnattachedSwitchControllers 0x33D
  FortRuntimeOptions::bDisableTouchLookVelocityScaling 0x33E
  FortRuntimeOptions::bDisablePurchaseHistoryScreen 0x33F
  FortRuntimeOptions::bEnableRedeemOfflinePurchasesToasts 0x340
  FortRuntimeOptions::bAllowProcessedPayoutsToRefreshProfile 0x341
  FortRuntimeOptions::TouchAimAssistStrengthScalar 0x344
  FortRuntimeOptions::bDisableTouchAimAssistAutoTracking 0x348
  FortRuntimeOptions::bProcessGamepadInputOnMobile 0x349
  FortRuntimeOptions::bMobileForceGamepadHUDWhenAttached 0x34A
  FortRuntimeOptions::bDisableLegacyControls 0x34B
  FortRuntimeOptions::bFixAimAssistDeadzoneExploit 0x34C
  FortRuntimeOptions::CrucibleWhitelistOverride 0x34D
  FortRuntimeOptions::bDisableCrucibleStatUpload 0x34E
  FortRuntimeOptions::bDisableCrucibleStatDownload 0x34F
  FortRuntimeOptions::bDisableCrucibleGlobalLeaderboards 0x350
  FortRuntimeOptions::bDisableCrucibleFriendLeaderboards 0x351
  FortRuntimeOptions::bDisableCrucibleAnalyticsEvents 0x352
  FortRuntimeOptions::bDisableCrucibleDestroyDeadBots 0x353
  FortRuntimeOptions::bDisableCrucibleForcedGC 0x354
  FortRuntimeOptions::bDisableCrucibleLeaderboardFilterText 0x355
  FortRuntimeOptions::bDisableCrucibleLeaderboardSwitching 0x356
  FortRuntimeOptions::bCrucibleLockToPlatform 0x357
  FortRuntimeOptions::bCrucibleSendStatsEndOfSession 0x358
  FortRuntimeOptions::bCrucibleSendStatsEndOfSessionOnShutdownEvent 0x359
  FortRuntimeOptions::CrucibleMinValidStatScoreMilliseconds 0x35C
  FortRuntimeOptions::CrucibleLeaderboardFriendQueryMaxSize 0x360
  FortRuntimeOptions::bCrucibleLeaderboardEnableDisplayNameIcons 0x364
  FortRuntimeOptions::bEnableFortLeaderboardHelperDisplayNonPlatformNames 0x365
  FortRuntimeOptions::bEnableFortLeaderboardHelperConsolePlatformNameSearch 0x366
  FortRuntimeOptions::bEnableFortLeaderboardHelperConsoleDisplayNameFallback 0x367
  FortRuntimeOptions::bDisableCollectionStatsUpload 0x368
  FortRuntimeOptions::bDisableCollectionStatsDownload 0x369
  FortRuntimeOptions::CollectionStatsFriendQueryMaxSize 0x36C
  FortRuntimeOptions::bUseNativeQuickbar 0x370
  FortRuntimeOptions::bSoundIndicatorsAlwaysEnabled 0x371
  FortRuntimeOptions::bSoundIndicatorsEnabledForTeammates 0x372
  FortRuntimeOptions::bSoundIndicatorsPooled 0x373
  FortRuntimeOptions::SoundIndicatorMaxNum 0x374
  FortRuntimeOptions::TencentDefaultBookStatSeason 0x378
  FortRuntimeOptions::bEquipFirstWeaponOnMobile 0x37C
  FortRuntimeOptions::bClearLastFireOnAbilityFailed 0x37D
  FortRuntimeOptions::bUsePrototypeSubGameLoadingScreen 0x37E
  FortRuntimeOptions::bForcePrototypeLoadingScreenScaling 0x37F
  FortRuntimeOptions::ShowEliminationDistanceOver 0x380
  FortRuntimeOptions::FadeOutTeamIndicatorsAfter 0x384
  FortRuntimeOptions::FadeOutNPCEnemyIndicatorsAfter 0x388
  FortRuntimeOptions::FadeOutEnemyIndicatorsAfter 0x38C
  FortRuntimeOptions::FadeOutWorldItemIndicatorsAfter 0x390
  FortRuntimeOptions::FadeOutHardCoreBeaconIndicatorsAfter 0x394
  FortRuntimeOptions::MapIndicatorTouchClearDistance 0x398
  FortRuntimeOptions::MapIndicatorOffset 0x39C
  FortRuntimeOptions::AthenaMapZoomMax 0x3A4
  FortRuntimeOptions::BacchusMapIndicatorSizeMultiplier 0x3A8
  FortRuntimeOptions::AthenaMapPanSpeedMultiplier 0x3AC
  FortRuntimeOptions::AthenaMapZoomSpeedMultiplier 0x3B0
  FortRuntimeOptions::bAthenaMapMapIconsFlowEnabled 0x3B4
  FortRuntimeOptions::WaitTimeBeforeShowingNewModeViolator 0x3B8
  FortRuntimeOptions::FriendCodeShareWarningMessage 0x3C0
  FortRuntimeOptions::PlatformPlayAllowedErrorMessage 0x3D0
  FortRuntimeOptions::bOnlyShareURLWithNoMessage 0x3E0
  FortRuntimeOptions::bExcludeURLInShareMessage 0x3E1
  FortRuntimeOptions::bShowCreateAccountOnRedirect 0x3E2
  FortRuntimeOptions::bEnableContextTutorial 0x3E3
  FortRuntimeOptions::bDebugForcePlayerSurveys 0x3E4
  FortRuntimeOptions::bFeedbackTextShown 0x3E5
  FortRuntimeOptions::bEnableBadMatchPopup 0x3E6
  FortRuntimeOptions::BadMatchIncidentThreshold 0x3E8
  FortRuntimeOptions::BadConnectionUpdateTime 0x3EC
  FortRuntimeOptions::BadMatchPopupRecallInterval 0x3F0
  FortRuntimeOptions::AthenaCodeOfConductURL 0x3F8
  FortRuntimeOptions::KairosCommunityRulesURL 0x408
  FortRuntimeOptions::BacchusFriendCodeShareURL 0x418
  FortRuntimeOptions::CreateAccountUrl 0x428
  FortRuntimeOptions::GooglePlayRatingURL 0x438
  FortRuntimeOptions::LinkAccountURL 0x448
  FortRuntimeOptions::AccountMergeMoreInfoURL 0x458
  FortRuntimeOptions::bEnableFactionTechScreen 0x468
  FortRuntimeOptions::bRequireFactionChoiceOnInfiltrationPlay 0x469
  FortRuntimeOptions::TotalPlayerTechLevelsToShow 0x46C
  FortRuntimeOptions::SupportURL 0x470
  FortRuntimeOptions::CheckStatusURL 0x480
  FortRuntimeOptions::iOSAppStoreURL 0x490
  FortRuntimeOptions::TurnOnMfaURL 0x4A0
  FortRuntimeOptions::ArenaResetTime 0x4B0
  FortRuntimeOptions::ListOfCreatorsURL 0x4C0
  FortRuntimeOptions::bAllowCodeRedemptionInSubgameSelect 0x4D0
  FortRuntimeOptions::bEnableAutomaticMOTD 0x4D1
  FortRuntimeOptions::bShowMOTDInLobby 0x4D2
  FortRuntimeOptions::bMOTDSameNewsForCreative 0x4D3
  FortRuntimeOptions::bSkipSubgameSelect 0x4D4
  FortRuntimeOptions::BRUpdatesURLMode 0x4D5
  FortRuntimeOptions::BRUpdatesURL 0x4D8
  FortRuntimeOptions::STWUpdatesURLMode 0x4E8
  FortRuntimeOptions::STWUpdatesURL 0x4F0
  FortRuntimeOptions::GiftingInfoURL 0x500
  FortRuntimeOptions::PrivacyPolicyURL 0x510
  FortRuntimeOptions::FanContentPolicyURL 0x520
  FortRuntimeOptions::TermsOfServiceURL 0x530
  FortRuntimeOptions::GuardianChallengeLengthDays 0x540
  FortRuntimeOptions::bAgeGateFlowEnabled 0x544
  FortRuntimeOptions::bEnableContentControls 0x545
  FortRuntimeOptions::ContentControlsMoreInfoURL 0x548
  FortRuntimeOptions::ContentControlsForgotPinURL 0x558
  FortRuntimeOptions::ContentControlsVerifyEmailURL 0x568
  FortRuntimeOptions::bEnableContentControlsPlaytimeReporting 0x578
  FortRuntimeOptions::bEnableContentControlsPurchaseReporting 0x579
  FortRuntimeOptions::bContentControlsViewUGCEnabled 0x57A
  FortRuntimeOptions::MaxNumItemsInCreativeChests 0x57C
  FortRuntimeOptions::MaxStackSizeForCreativeResources 0x580
  FortRuntimeOptions::MaxStreamerMatchmakingDelay 0x584
  FortRuntimeOptions::bEnableHiddenMatchmakingDelay 0x588
  FortRuntimeOptions::TencentStoreDetailsURL 0x590
  FortRuntimeOptions::PSALoadingScreenPercentChance 0x5A0
  FortRuntimeOptions::StwDownloadLauncherOption 0x5A8
  FortRuntimeOptions::OverrideDefaultBonusXpEventTitleString 0x5B8
  FortRuntimeOptions::XBLDisableText 0x5C8
  FortRuntimeOptions::PSNDisableText 0x5D8
  FortRuntimeOptions::SwitchDisableText 0x5E8
  FortRuntimeOptions::ReviewPromptCriteria 0x5F8
  FortRuntimeOptions::bDisableAllKnobs 0x60C
  FortRuntimeOptions::bDisableAllGameplayMessages 0x60D
  FortRuntimeOptions::bDisableMatchmakingKnobs 0x60E
  FortRuntimeOptions::bDisableMinigameKnobs 0x60F
  FortRuntimeOptions::bDisableGameOptionKnobs 0x610
  FortRuntimeOptions::bDisableAffiliateFeature 0x611
  FortRuntimeOptions::bUseHotfixedAffiliateNamesArray 0x612
  FortRuntimeOptions::bEnablePrerollLlamas 0x613
  FortRuntimeOptions::bEnableSubregionNetworkAccelerators 0x614
  FortRuntimeOptions::DisabledNetworkAcceleratedSubregions 0x618
  FortRuntimeOptions::AdvertisedNetworkAcceleratedSubregions 0x628
  FortRuntimeOptions::bShowAccountItemWarningForVaultThreshold 0x638
  FortRuntimeOptions::DaysBetweenAccountItemWarnings 0x63C
  FortRuntimeOptions::VaultLimitThresholdForAccountItemWarning 0x640
  FortRuntimeOptions::bShowAccountItemWarningForItemCount 0x644
  FortRuntimeOptions::AlwaysWarnAccountItemCount 0x648
  FortRuntimeOptions::DisabledFrontendNavigationTabs 0x650
  FortRuntimeOptions::DisabledTabsForOutOfSeason 0x660
  FortRuntimeOptions::TournamentDisabledFrontendNavigationTabs 0x670
  FortRuntimeOptions::DisabledMatchmakingKnobs 0x680
  FortRuntimeOptions::HiddenMatchmakingKnobs 0x690
  FortRuntimeOptions::DisabledGameplayMessages 0x6A0
  FortRuntimeOptions::NumGameplayMessageChannels 0x6B0
  FortRuntimeOptions::AffiliateNames 0x6B8
  FortRuntimeOptions::bShowMOTDNews 0x6C8
  FortRuntimeOptions::DPlusVBuckPromoStart 0x6D0
  FortRuntimeOptions::DPlusVBuckPromoEnd 0x6D8
  FortRuntimeOptions::CountryCodesForDPlusVBuckOverride 0x6E0
  FortRuntimeOptions::RockyRidgeStart 0x6F0
  FortRuntimeOptions::SoloTournamentScoreThresholds 0x6F8
  FortRuntimeOptions::DuoTournamentScoreThresholds 0x708
  FortRuntimeOptions::SquadsTournamentScoreThresholds 0x718
  FortRuntimeOptions::PickingInteractDistance 0x728
  FortRuntimeOptions::PickingHighlightMovementUpdateDist 0x72C
  FortRuntimeOptions::PickingHighlightUpdateTime 0x730
  FortRuntimeOptions::PickingTime 0x734
  FortRuntimeOptions::AutoPickingInteractDistanceFactor 0x738
  FortRuntimeOptions::AutoOpenDoorInputMagnitude 0x73C
  FortRuntimeOptions::AutoOpenDoorTraceDistance 0x740
  FortRuntimeOptions::bAutofireEnabled 0x744
  FortRuntimeOptions::bShowXPWidgets 0x745
  FortRuntimeOptions::bShowAccoladesListWidget 0x746
  FortRuntimeOptions::bEnableInGameMatchmaking 0x747
  FortRuntimeOptions::bUseNewFlowIngameMatchmaking 0x748
  FortRuntimeOptions::bDisableAccoladesButton 0x749
  FortRuntimeOptions::bToggleIGMAnalytics 0x74A
  FortRuntimeOptions::WhitelistedInGameMatchmakingRegions 0x750
  FortRuntimeOptions::WhitelistedInGameMatchmakingSubRegions 0x760
  FortRuntimeOptions::BlacklistedInGameMatchmakingSubRegions 0x770
  FortRuntimeOptions::BlacklistedInGameMatchmakingPlaylists 0x780
  FortRuntimeOptions::SubRegionWhitelistedInGameMatchmakingPlaylists 0x790
  FortRuntimeOptions::bAllowPreserveSquad 0x7A0
  FortRuntimeOptions::bAllowPreserveSquadMemberVoting 0x7A1
  FortRuntimeOptions::bKeepPlayingTogether 0x7A2
  FortRuntimeOptions::bPartyRift 0x7A3
  FortRuntimeOptions::bPartyRiftAllowJoinOnPrivate 0x7A4
  FortRuntimeOptions::bAutofireUsesComponent 0x7A5
  FortRuntimeOptions::bAutofireUsesAutoaimTarget 0x7A6
  FortRuntimeOptions::bHoldToFireOnAutofireTarget 0x7A7
  FortRuntimeOptions::DefaultAutofireRange 0x7A8
  FortRuntimeOptions::AutofireExtraTrackingRange 0x7AC
  FortRuntimeOptions::bServerNetDriverAnalytics 0x7B0
  FortRuntimeOptions::bClientNetDriverAnalytics 0x7B1
  FortRuntimeOptions::bDisableReplicationGraph 0x7B2
  FortRuntimeOptions::BRServerMaxTickRate 0x7B4
  FortRuntimeOptions::DoubleTapOnEndTouchTime 0x7B8
  FortRuntimeOptions::DoubleTapOnStartTouchTime 0x7BC
  FortRuntimeOptions::DoubleTapDistance 0x7C0
  FortRuntimeOptions::SingleTapDistance 0x7C4
  FortRuntimeOptions::TouchMoveStickRadius 0x7C8
  FortRuntimeOptions::TouchMoveStickRadiusTargeting 0x7CC
  FortRuntimeOptions::TouchMoveStickRadiusScoped 0x7D0
  FortRuntimeOptions::TouchMoveStickRadiusDriving 0x7D4
  FortRuntimeOptions::AutorunLockZoneOffset 0x7D8
  FortRuntimeOptions::AutorunLockZoneDelay 0x7DC
  FortRuntimeOptions::MoveOriginResetTime 0x7E0
  FortRuntimeOptions::MoveOriginResetDistance 0x7E4
  FortRuntimeOptions::MoveOriginFollowDistance 0x7E8
  FortRuntimeOptions::bDisableTouchLookInertia 0x7EC
  FortRuntimeOptions::RotateInertiaMultiplier 0x7F0
  FortRuntimeOptions::RotateInertiaMinTime 0x7F4
  FortRuntimeOptions::RotateInertiaMinLength 0x7F8
  FortRuntimeOptions::RotateInertiaMinMagnitude 0x7FC
  FortRuntimeOptions::RotateInertiaNumAveragedTouches 0x800
  FortRuntimeOptions::bTouchQuickbarTapToLockEnabled 0x804
  FortRuntimeOptions::bTouchInteractInUIAvailable 0x805
  FortRuntimeOptions::bTouchInteractInUIForced 0x806
  FortRuntimeOptions::bEnableHUDLayoutTool 0x807
  FortRuntimeOptions::bEnableHUDLayoutCloudSave 0x808
  FortRuntimeOptions::bEnableHUDLayoutToolPanZoom 0x809
  FortRuntimeOptions::bEnableMobileHUDV2 0x80A
  FortRuntimeOptions::bEnableHUDLayoutToolV2 0x80B
  FortRuntimeOptions::bEnableHUDLayoutToolV2_GridSnap 0x80C
  FortRuntimeOptions::bEnableGFNSettingEditCondition 0x80D
  FortRuntimeOptions::AthenaExternalRichPresenceDelayTimeSeconds 0x810
  FortRuntimeOptions::bEnableExternalPresenceAthenaPlayersRemain 0x814
  FortRuntimeOptions::MinimumTimeBetweenConsolePresenceUpdates 0x818
  FortRuntimeOptions::MinimumTimeBetweenMCPPresenceUpdates 0x81C
  FortRuntimeOptions::TimeBetweenStorePatchCheckRequestsSeconds 0x820
  FortRuntimeOptions::bInviteUIDisabled 0x824
  FortRuntimeOptions::bEnableInGameMipsAnalyticsReporting 0x825
  FortRuntimeOptions::SecondsBetweenTextureStatsGathering 0x828
  FortRuntimeOptions::bEnableMipsCapExperiment 0x82C
  FortRuntimeOptions::CurrentMipsCapExperimentVersion 0x830
  FortRuntimeOptions::bEnableQualitySelectionScreen 0x834
  FortRuntimeOptions::bEnableQualityLevelSelectScreenTimer 0x835
  FortRuntimeOptions::bEnableDownloadAnalyticsReporting 0x836
  FortRuntimeOptions::bEnableDownloadHeartbeat 0x837
  FortRuntimeOptions::DownloadHeartbeatIntervalInSeconds 0x838
  FortRuntimeOptions::bEnableFriendsListButton 0x83C
  FortRuntimeOptions::bForceDisableCrossplatformSquadFill 0x83D
  FortRuntimeOptions::bRequireCrossplayOptIn 0x83E
  FortRuntimeOptions::bUseAccountCrossplayPermissions 0x83F
  FortRuntimeOptions::bSingleCrossplayOptInPrompt 0x840
  FortRuntimeOptions::bImmediatelyDisplayCrossplayOptIn_STW 0x841
  FortRuntimeOptions::bImmediatelyDisplayCrossplayOptIn_BR 0x842
  FortRuntimeOptions::bCrossplayOptInByDefault 0x843
  FortRuntimeOptions::bShowIconForSamePlatformPlayers 0x844
  FortRuntimeOptions::bObscuredPlatformIcons 0x845
  FortRuntimeOptions::bEnableChatWidget 0x846
  FortRuntimeOptions::bShowVoiceChatSettings 0x847
  FortRuntimeOptions::bShowMultipleVoiceChatSettings 0x848
  FortRuntimeOptions::bUseClientSettingsForControllerImage 0x849
  FortRuntimeOptions::bPartyInProgress 0x84A
  FortRuntimeOptions::bEnableSidebar 0x84B
  FortRuntimeOptions::bEnableHotTamaleWithVeggies 0x84C
  FortRuntimeOptions::bEnableHotTamale 0x84D
  FortRuntimeOptions::bEnableHotTamaleWithCheese 0x84E
  FortRuntimeOptions::bEnableHotTamaleWithOnions 0x84F
  FortRuntimeOptions::bEnableHotTamaleWithRice 0x850
  FortRuntimeOptions::bEnableHotTamaleWithTofu 0x851
  FortRuntimeOptions::MinTimeIntervalForHotTamalesWithColdVeggies 0x858
  FortRuntimeOptions::MinTimeIntervalForHotTamalesWithColdTofu 0x860
  FortRuntimeOptions::SidebarTooltipTimer 0x868
  FortRuntimeOptions::bShouldAthenaQueryRecentPlayers 0x86C
  FortRuntimeOptions::bEnableRecentPlayerList 0x86D
  FortRuntimeOptions::bEnableSuggestedFriendList 0x86E
  FortRuntimeOptions::bEnableBlockedList 0x86F
  FortRuntimeOptions::bEnableFriendListInGame 0x870
  FortRuntimeOptions::bPushJIPInfoToPlatformPresence 0x871
  FortRuntimeOptions::bEnableStWInZonePrivacyChange 0x872
  FortRuntimeOptions::bEnableSitoutOption 0x873
  FortRuntimeOptions::bEnableSitoutOption_STW 0x874
  FortRuntimeOptions::bEnableSocialPanelLeaveParty 0x875
  FortRuntimeOptions::bEnableMainMenuLeaveParty 0x876
  FortRuntimeOptions::MinUSSNameLength 0x878
  FortRuntimeOptions::bEnableNickname 0x87C
  FortRuntimeOptions::bAllowNicknameEmoji 0x87D
  FortRuntimeOptions::NicknameEmojiBlacklist 0x880
  FortRuntimeOptions::bNicknameInFront 0x890
  FortRuntimeOptions::bShowAccountBoosts 0x891
  FortRuntimeOptions::bShowCustomerSupport 0x892
  FortRuntimeOptions::bEnableChannelChangePopup 0x893
  FortRuntimeOptions::bEnableVoiceSpeakerWidget 0x894
  FortRuntimeOptions::bEnableSpeakerWidgetZonePerfMode 0x895
  FortRuntimeOptions::bShowVoiceIndicatorsWhileLoading 0x896
  FortRuntimeOptions::bEnableVoiceChannelSelectionUI 0x897
  FortRuntimeOptions::bEnableGlobalChat 0x898
  FortRuntimeOptions::bEnableAllTabInChat 0x899
  FortRuntimeOptions::bEnableEULA 0x89A
  FortRuntimeOptions::bEnableEndOfZoneCinematic 0x89B
  FortRuntimeOptions::bEnableOnboardingCinematics 0x89C
  FortRuntimeOptions::VideoDisplayDataBlacklist 0x8A0
  FortRuntimeOptions::bShowFounderBannerIcons 0x8B0
  FortRuntimeOptions::bShowCurrentRegionInLobby 0x8B1
  FortRuntimeOptions::bEnableFoundersDailyRewards 0x8B2
  FortRuntimeOptions::bEnableTwitchIntegration 0x8B3
  FortRuntimeOptions::bEnableMatchmakingRegionSetting 0x8B4
  FortRuntimeOptions::bEnableReadyupButtonWhileSittingout 0x8B5
  FortRuntimeOptions::bEnableEulaRequiredTournaments 0x8B6
  FortRuntimeOptions::bEnableMFARequiredTournaments 0x8B7
  FortRuntimeOptions::bAllTournamentsRequireMFA 0x8B8
  FortRuntimeOptions::bSpectatorBroadcasterSkipMfaEulaCheck 0x8B9
  FortRuntimeOptions::bEnableNaviationToChat 0x8BA
  FortRuntimeOptions::bEnableLanguageSetting 0x8BB
  FortRuntimeOptions::bEnableFriendCodeSetting 0x8BC
  FortRuntimeOptions::bEnableEarlyAccessLoadingScreenBanner 0x8BD
  FortRuntimeOptions::bClientIgnoreIsTournamentCheck 0x8BE
  FortRuntimeOptions::CampaignMatchEndRetryCount 0x8C0
  FortRuntimeOptions::StWTutorialDownloadAttempts 0x8C4
  FortRuntimeOptions::bShopPurchaseConfirmation 0x8C8
  FortRuntimeOptions::bShopPurchaseConfirmationJapanPS4 0x8C9
  FortRuntimeOptions::bToyMessagingEnabled 0x8CA
  FortRuntimeOptions::bAllowAccessToAllEmotesForTesting 0x8CB
  FortRuntimeOptions::bAllowAccessToStWHeroOutfitsAndBackblingForTesting 0x8CC
  FortRuntimeOptions::bEnableCosmeticItemShopInSTW 0x8CD
  FortRuntimeOptions::bRequireEmoteOwnershipInPIE 0x8CE
  FortRuntimeOptions::bEnableSTWLootDrops 0x8CF
  FortRuntimeOptions::bEnableSTWContainerItemCacheDrops 0x8D0
  FortRuntimeOptions::bEnableSTWEnemyItemCacheDrops 0x8D1
  FortRuntimeOptions::bEnableHoldToPickupUI 0x8D2
  FortRuntimeOptions::bSkipTrailerMovie 0x8D3
  FortRuntimeOptions::bAlwaysPlayTrailerMovie 0x8D4
  FortRuntimeOptions::bHideUnaffordableMtxPurchases 0x8D5
  FortRuntimeOptions::bDisableCTAInMtxStoreSelection 0x8D6
  FortRuntimeOptions::bAthenaFrontEndUsePushPopMTXStore 0x8D7
  FortRuntimeOptions::bHidePlusOnVbucksButton 0x8D8
  FortRuntimeOptions::bAllowXboxStwAccessDuringLiveStoreOutage 0x8D9
  FortRuntimeOptions::bShowReplayTrailerButton_Athena 0x8DA
  FortRuntimeOptions::bEnableAlterationModification 0x8DB
  FortRuntimeOptions::bEnableSchematicRarityUpgrade 0x8DC
  FortRuntimeOptions::bEnableMissionActivationVote 0x8DD
  FortRuntimeOptions::bEnableLtmRetrieveTheData 0x8DE
  FortRuntimeOptions::bEnableUpgradesVideos 0x8DF
  FortRuntimeOptions::bEnableExternalRichPresence 0x8E0
  FortRuntimeOptions::bShowEnableMFAModalAtStartupAthena 0x8E1
  FortRuntimeOptions::bShowEnableMFAModalAtStartupSTW 0x8E2
  FortRuntimeOptions::bEnableAIBuildingHitFX 0x8E3
  FortRuntimeOptions::LevelToStartShowingMFAModal 0x8E4
  FortRuntimeOptions::DaysBetweenEnableMFAModalPrompts 0x8E8
  FortRuntimeOptions::DelayGiftButtonWhenMFANotEnabledSeconds 0x8EC
  FortRuntimeOptions::LevelToAutoOpenBattlePassOnNewSeason 0x8F0
  FortRuntimeOptions::ForceSeasonRefreshCounter 0x8F4
  FortRuntimeOptions::ForceVideoRefreshCounter 0x8F8
  FortRuntimeOptions::bForceBattlePassPreview 0x8FC
  FortRuntimeOptions::bCanShowSTWUpsellInBR 0x8FD
  FortRuntimeOptions::bShowLeaderboardPrivacySettings 0x8FE
  FortRuntimeOptions::bEnableServerScoreboardLog 0x8FF
  FortRuntimeOptions::bEnableAsyncScoreboardFlush 0x900
  FortRuntimeOptions::bEnableInputBasedMatchmaking 0x901
  FortRuntimeOptions::bUsingAlternateMatchmakingModel 0x902
  FortRuntimeOptions::bNotifyBlockedInput 0x903
  FortRuntimeOptions::NumberOfFramesBeforeWarnInputBlocked 0x904
  FortRuntimeOptions::bDisableVideoOptions 0x908
  FortRuntimeOptions::bEnableBattlePassWatchVideoActionOnCell 0x909
  FortRuntimeOptions::bEnableBattlePassReplayCinematicAction 0x90A
  FortRuntimeOptions::bEnableCareerReplayCinematicAction 0x90B
  FortRuntimeOptions::RadioInputDebounceSeconds 0x90C
  FortRuntimeOptions::RadioTuningRetryTime 0x910
  FortRuntimeOptions::RadioTuningRetryCount 0x914
  FortRuntimeOptions::bEnableBattlePassSocialFriends 0x918
  FortRuntimeOptions::bEnableBattlePassSocialFriendsOfDifferentPlatforms 0x919
  FortRuntimeOptions::bEnableBattlePassSocialFriendsServerSide 0x91A
  FortRuntimeOptions::bEnableSimulatedXPForBattlePassSocialFriends 0x91B
  FortRuntimeOptions::bEnableBattlePassPreviewOnRewardScreen 0x91C
  FortRuntimeOptions::bEnableHoldToCloseOnRewardsScreen 0x91D
  FortRuntimeOptions::BattleStarsNeededToShowRewardPreview 0x920
  FortRuntimeOptions::ShowBattlePassTracker 0x924
  FortRuntimeOptions::bDisplayBattlePassRewardsIndividually 0x928
  FortRuntimeOptions::bDisplayOnlyBattlePassFAQ 0x929
  FortRuntimeOptions::bEnableBPVideo 0x92A
  FortRuntimeOptions::bEnableUEKGameSelect 0x92B
  FortRuntimeOptions::bCompletelyDisableUEKGameSelect 0x92C
  FortRuntimeOptions::bAlwaysPlayBPVideo 0x92D
  FortRuntimeOptions::bDisableGRL 0x92E
  FortRuntimeOptions::bShowBPPreviewVideo 0x92F
  FortRuntimeOptions::bShowBPTrack_TimeLeft 0x930
  FortRuntimeOptions::bDisplayAllCharactersOnBattlePassPreviewScreen 0x931
  FortRuntimeOptions::bRefreshBattlePassCatalogOnSeasonDataLoaded 0x932
  FortRuntimeOptions::bEnableChallengeHolidayVideo 0x933
  FortRuntimeOptions::bEnableCareerScreenVideo 0x934
  FortRuntimeOptions::bEnableSpecialEventVideo 0x935
  FortRuntimeOptions::bEnableCNVideo 0x936
  FortRuntimeOptions::bEnableWinterfestPurchaseButton 0x937
  FortRuntimeOptions::bEnableWinterfestGiftButton 0x938
  FortRuntimeOptions::bForceWinterfestInfoModalButtonVisible 0x939
  FortRuntimeOptions::NumViewsToDisplayWinterfestInfoModalButton 0x93C
  FortRuntimeOptions::bCheckForPatchUpdateOnMatchmakingPlayClick 0x940
  FortRuntimeOptions::bCheckForPatchUpdateOnItemShopActivate 0x941
  FortRuntimeOptions::HiddenSettings 0x948
  FortRuntimeOptions::bDisplayPlayerReportingRoles 0x958
  FortRuntimeOptions::bDisplayRelevantPlayersForPlayerReporting 0x959
  FortRuntimeOptions::bPreventMultipleReportsOfSamePlayer 0x95A
  FortRuntimeOptions::bAllowReportingFeaturedIslands 0x95B
  FortRuntimeOptions::bForceGamepadPlaytest 0x95C
  FortRuntimeOptions::bEnableNewFireModeSelection 0x95D
  FortRuntimeOptions::bEnableHUDPresetSelection 0x95E
  FortRuntimeOptions::bEnableAddFriendWhileSpectating 0x95F
  FortRuntimeOptions::bEnableFriendLink 0x960
  FortRuntimeOptions::PlatformChatToastDisplaySeconds 0x964
  FortRuntimeOptions::HPMicrophoneToastDisplaySeconds 0x968
  FortRuntimeOptions::FriendLinkURL 0x970
  FortRuntimeOptions::bAllowForceTouchFire 0x980
  FortRuntimeOptions::VehicleSessionMinTimeUsed 0x984
  FortRuntimeOptions::RebootChipExpirationTime 0x988
  FortRuntimeOptions::RebootDirectiveDisplayTime 0x98C
  FortRuntimeOptions::bDonutIdleGameEnabled 0x990
  FortRuntimeOptions::bRebootEnableInventoryDisplay 0x991
  FortRuntimeOptions::bUseHordeStormShield 0x992
  FortRuntimeOptions::HordeStormShieldStartingRadiusOverride 0x994
  FortRuntimeOptions::HordeStormShieldEndingRadiusOverride 0x998
  FortRuntimeOptions::HordeStormShieldBreatherRadiusOverride 0x99C
  FortRuntimeOptions::bUseHordeRespawnAtLastPawnLocation 0x9A0
  FortRuntimeOptions::bAllowHordePlayerTriggeredRespawn 0x9A1
  FortRuntimeOptions::MaxQuickScopeAimAssistPulls 0x9A4
  FortRuntimeOptions::MaxQuickScopeAimAssistPullWatchTime 0x9A8
  FortRuntimeOptions::bShouldDisablePickaxeFXFrontendPreview 0x9AC
  FortRuntimeOptions::bRegisterPawnsWithSignificanceManagerInFrontEnd 0x9AD
  FortRuntimeOptions::bHideExclusiveCosmeticsFromOtherPlatformsOnPS4 0x9AE
  FortRuntimeOptions::bHideExclusiveCosmeticsFromOtherPlatformsOnXB1 0x9AF
  FortRuntimeOptions::bHideExclusiveCosmeticsFromOtherPlatformsOnSwitch 0x9B0
  FortRuntimeOptions::bHideExclusiveCosmeticsFromOtherPlatformsOnPS4_STWOnly 0x9B1
  FortRuntimeOptions::bHideExclusiveCosmeticsFromOtherPlatformsOnXB1_STWOnly 0x9B2
  FortRuntimeOptions::bHideExclusiveCosmeticsFromOtherPlatformsOnSwitch_STWOnly 0x9B3
  FortRuntimeOptions::bSimpleHeistVanEntrance 0x9B4
  FortRuntimeOptions::LobbyGenericLinkButtonURL 0x9B8
  FortRuntimeOptions::bEnableLobbyGenericLinkButton 0x9C8
  FortRuntimeOptions::LobbyGenericLinkButtonText 0x9D0
  FortRuntimeOptions::HighlightClipRewindTimeInSeconds 0x9E0
  FortRuntimeOptions::bEnableAntiTaxi 0x9E4
  FortRuntimeOptions::StopFlyingParachuteCooldownTime 0x9E8
  FortRuntimeOptions::FlushLoadingScreenRefreshSeconds 0x9EC
  FortRuntimeOptions::bEnableVehicleSpawnMissionInStw 0x9F0
  FortRuntimeOptions::bEnableDownTierCraftingInStw 0x9F1
  FortRuntimeOptions::bShowBugReportsButton 0x9F2
  FortRuntimeOptions::bShowCommentReportsButton 0x9F3
  FortRuntimeOptions::bShowContentReportsButton 0x9F4
  FortRuntimeOptions::bEnableItemRefundingInStw 0x9F5
  FortRuntimeOptions::bDisableCareerStatsButton 0x9F6
  FortRuntimeOptions::bDisableCareerLeaderboardButton 0x9F7
  FortRuntimeOptions::bDisableCareerStatsPagePlatformProfileButton 0x9F8
  FortRuntimeOptions::bUsePlatformSpecificTextOnCareerPage 0x9F9
  FortRuntimeOptions::bDisableViewOtherProfilesFromCompLeaderboards 0x9FA
  FortRuntimeOptions::bShowOtherPlayerStatsOnCareerPage 0x9FB
  FortRuntimeOptions::bShowFeatsOnClient 0x9FC
  FortRuntimeOptions::bShowHardcoreModifiers 0x9FD
  FortRuntimeOptions::InputMethodThrashingLimit 0xA00
  FortRuntimeOptions::InputMethodThrashingWindowInSeconds 0xA04
  FortRuntimeOptions::bEnableLogUploadForTokenHolders 0xA08
  FortRuntimeOptions::TokenHolderLogTailSizeKb 0xA0C
  FortRuntimeOptions::bAllowPartialBackgroundAudio 0xA10
  FortRuntimeOptions::bDuplicateRemovedPlayersOnClient 0xA11
  FortRuntimeOptions::PlayerMarkerConfig 0xA14
  FortRuntimeOptions::bIsCreativeMultiSelectEnabled 0xA70
  FortRuntimeOptions::bEnableUserProfilePictures 0xA71
  FortRuntimeOptions::bEnableChannelsServiceLoadTesting 0xA72
  FortRuntimeOptions::bAllowMimicingEmotes 0xA73
  FortRuntimeOptions::bAllowMimicingEmotesInFrontend 0xA74
  FortRuntimeOptions::bAllowAsyncTooltipLoading 0xA75
  FortRuntimeOptions::bAllowListViewAsyncLoading 0xA76
  FortRuntimeOptions::bEnableBackToPartyHubButton 0xA77
  FortRuntimeOptions::bEnableMobileAvailableLootingListView 0xA78
  FortRuntimeOptions::bEnableDisambiguateLoading 0xA79
  FortRuntimeOptions::NumDaysToSnoozeGooglePlayRating 0xA7C
  FortRuntimeOptions::NumDaysAllowedToDelayGoogleRating 0xA80
  FortRuntimeOptions::bEnableMobileInGameAppRating 0xA84
  FortRuntimeOptions::PreloadRevision 0xA88
  FortRuntimeOptions::bEnableLiveStoreTilePreviews 0xA8C
  FortRuntimeOptions::bUseLegacyItemShopOfferDetails 0xA8D
  FortRuntimeOptions::bEnableLiveStoreTilePreviews_InGame 0xA8E
  FortRuntimeOptions::bAllowedToEnableUIGlobalInvalidation 0xA8F
  FortRuntimeOptions::bEnableAutoMulchInStW 0xA90
  FortRuntimeOptions::bAllStWMoonbeamHUD 0xA91
  FortRuntimeOptions::MaxCharactersInTextEntry 0xA94
  FortRuntimeOptions::IllegalIslandTitleCharacters 0xA98
  FortRuntimeOptions::IllegalIslandTitleChars 0xAA8
  FortRuntimeOptions::bEnableCreativeUserTextSanitizationWithToxicityService 0xAB8
  FortRuntimeOptions::bEnableCreativeUserTextSanitizationWithPlatformSanitizer 0xAB9
  FortRuntimeOptions::bEnableCreativeUserTextSanitizationWithChatSanitizer 0xABA
  FortRuntimeOptions::bUseToxicityAsCreativeMainTextSanitizer 0xABB
  FortRuntimeOptions::bUseLegacyAsyncSanitizationLogicInCreative 0xABC
  FortRuntimeOptions::KeepPlayingTogetherDuration 0xAC0
  FortRuntimeOptions::KeepPlayingTogetherTickFrequency 0xAC4
  FortRuntimeOptions::bUseLegacyFootsteps 0xAC8
  FortRuntimeOptions::PawnVisibilityDurationOverrides 0xAD0
  FortRuntimeOptions::HotfixVersionId 0xB20
  FortRuntimeOptions::bCanTurboBuildOutsideBuildModeWithBuildTool 0xB24
  FortRuntimeOptions::MaxBuildingIntoTerrainIntersectionPercentage 0xB28
  FortRuntimeOptions::bUsingBuildingExtraPiece 0xB2C
  FortRuntimeOptions::AnalyticsBuildingWallTooLowLocations 0xB30
  FortRuntimeOptions::bDisableClientEngagementsAnalytics 0xB34
  FortRuntimeOptions::AnalyticsClientEngagementsTimeoutSeconds 0xB38
  FortRuntimeOptions::AnalyticsClientEngagementsMaxSendPerMinute 0xB3C
  FortRuntimeOptions::AnalyticsClientEngagementsMaxSendOnCleanup 0xB40
  FortRuntimeOptions::bAnalyticsClientEngagementsRequireTimeToReturnFireToSend 0xB44
  FortRuntimeOptions::AnalyticsClientEngagementsParticipationPercent 0xB48
  FortRuntimeOptions::PublishingEnabledForWhitelistedAccounts 0xB4C
  FortRuntimeOptions::IslandCodeLinkMnemonicExampleText 0xB50
  FortRuntimeOptions::IslandCodeLinkURLText 0xB60
  FortRuntimeOptions::FeaturedCreativeLTMAffiliateName 0xB70
  FortRuntimeOptions::bEnableCreativeLTMSupportCreator 0xB80
  FortRuntimeOptions::CreativePublishCodeURLPrefix 0xB88
  FortRuntimeOptions::bCreativeMinimapRendering 0xB98
  FortRuntimeOptions::bCreativeMinimapCaptureLighting 0xB99
  FortRuntimeOptions::bCreativeMapRenderingInHub 0xB9A
  FortRuntimeOptions::bCreativeMapWaitForVolumeReady 0xB9B
  FortRuntimeOptions::CuratedLinkCodes 0xBA0
  FortRuntimeOptions::CuratedIslandTemplateCodes 0xBB0
  FortRuntimeOptions::PlaylistCuratedContent 0xBC0
  FortRuntimeOptions::bEnableIslandCheckpoints 0xC10
  FortRuntimeOptions::bEnableIslandLoadNetSafeGuards 0xC11
  FortRuntimeOptions::PlaylistCuratedHub 0xC18
  FortRuntimeOptions::CreativeIslandImageURLOverrides 0xC68
  FortRuntimeOptions::CreativeIslandGeneratedImageURLOverride 0xCB8
  FortRuntimeOptions::bLoadingScreenInputPreprocessorEnabled 0xCC8
  FortRuntimeOptions::AllowInputTypeFilterForAccessibility 0xCC9
  FortRuntimeOptions::AllowLockPrimaryInputMethodToMouseForAccessibility 0xCCA
  FortRuntimeOptions::bEnableLiveStream 0xCCB
  FortRuntimeOptions::bEnableLiveStreamCountdown 0xCCC
  FortRuntimeOptions::LiveStreamStartTime 0xCD0
  FortRuntimeOptions::bEnableLiveStreamInMatch 0xCD8
  FortRuntimeOptions::bShowLiveStreamInMatchByDefault 0xCD9
  FortRuntimeOptions::bCaptureTeamFrontendFlag 0xCDA
  FortRuntimeOptions::VideoHolidayName 0xCDC
  FortRuntimeOptions::VideoBattlePassName 0xCE4
  FortRuntimeOptions::VideoCareerScreenName 0xCEC
  FortRuntimeOptions::VideoChallengeScreenName 0xCF4
  FortRuntimeOptions::VideoFrontEndName 0xCFC
  FortRuntimeOptions::FTUESeasonTrailerBoundary 0xD04
  FortRuntimeOptions::VideoDurationOffsetFromTransition 0xD08
  FortRuntimeOptions::VideoDurationOffsetFromEnd 0xD0C
  FortRuntimeOptions::bEnableGCBeforeVideoPlayback 0xD10
  FortRuntimeOptions::EOneVideoLength 0xD14
  FortRuntimeOptions::ETwoVideoLength 0xD18
  FortRuntimeOptions::MediaCDNDistribution 0xD20
  FortRuntimeOptions::MaxNumberOfMediaDecoderResources 0xD30
  FortRuntimeOptions::VideoEVMap 0xD38
  FortRuntimeOptions::MediaPartnerRegionControl 0xD48
  FortRuntimeOptions::LiveStreamPiPMemoryRequired 0xD58
  FortRuntimeOptions::ShouldShowLiveStreamPiPInMatchCounter 0xD60
  FortRuntimeOptions::bEnableNewPIP 0xD68
  FortRuntimeOptions::bEnableRiskyReelsStreaming 0xD69
  FortRuntimeOptions::bDisableBlastURLStreamSource 0xD6A
  FortRuntimeOptions::StreamPlaylistFetchMethodOrder 0xD6C
  FortRuntimeOptions::bHiddenButEnabledLiveStreamInMatch 0xD70
  FortRuntimeOptions::TimedEventsJIPStartDelay 0xD74
  FortRuntimeOptions::bInputActionHolding 0xD78
  FortRuntimeOptions::PictureInPictureState 0xD79
  FortRuntimeOptions::bEnableSplineReticulationById 0xD7C
  FortRuntimeOptions::bUseSingleHUDUpdatePerFrame 0xD7D
  FortRuntimeOptions::MinInteractionScoreForFriendToBeConsideredClose 0xD80
  FortRuntimeOptions::MinIntervalBetweenInviteToPartyNotificationsInSeconds 0xD88
  FortRuntimeOptions::DelayBetweenStartOfPostGameAndShowDelayedNotificationsInSeconds 0xD90
  FortRuntimeOptions::PlaylistConditionalFlags 0xD98
  FortRuntimeOptions::bIsUserChoiceAllowedForForcedAndroidStore 0xDA8
  FortRuntimeOptions::AndroidStoreCounter 0xDAC
  FortRuntimeOptions::bHideCharacterCustomizationNullTile 0xDB0
  FortRuntimeOptions::bEnablePlaylistRequireCrossplay 0xDB1
  FortRuntimeOptions::bRequireCrossplayOptInForFill 0xDB2
  FortRuntimeOptions::bUseConcurrentCrossplayPromptGuard 0xDB3
  FortRuntimeOptions::MaxSquadSize 0xDB4
  FortRuntimeOptions::MaxPartySizeCampaign 0xDB8
  FortRuntimeOptions::MaxPartySizeAthena 0xDBC
  FortRuntimeOptions::bShouldFollowersSendSquadMatchmakingInfo 0xDC0
  FortRuntimeOptions::bAllowAthenaNavSystemForCreative 0xDC1
  FortRuntimeOptions::bEnablePlayerSurveys 0xDC2
  FortRuntimeOptions::bEnablePlayerStatsPrecache 0xDC3
  FortRuntimeOptions::bEnableStreamingReplayViewingUI 0xDC4
  FortRuntimeOptions::LiveReplayDiscoverabilityDelay 0xDC8
  FortRuntimeOptions::bSkipPlayingFortniteChecks 0xDCC
  FortRuntimeOptions::bReplayBattleMapCameraMode 0xDCD
  FortRuntimeOptions::bReplayKeepLocalClientEvents 0xDCE
  FortRuntimeOptions::bReplaySampleAthenaPawnMovement 0xDCF
  FortRuntimeOptions::ReplaySampleAthenaPawnTimeRate 0xDD0
  FortRuntimeOptions::ReplaySampleAthenaPawnSpaceRate 0xDD4
  FortRuntimeOptions::ReplaySampleAthenaPawnUpdateTimeRate 0xDD8
  FortRuntimeOptions::bDisablePartyJoinInOutpost 0xDDC
  FortRuntimeOptions::MashSpecialScores 0xDE0
  FortRuntimeOptions::bEnableMissedInvitesEntry 0xE30
  FortRuntimeOptions::bOnlyShowMissedInvitesEntryIfMissedInvites 0xE31
  FortRuntimeOptions::bEnableSidekick 0xE32
  FortRuntimeOptions::bEnableSidekickFeature1 0xE33
  FortRuntimeOptions::bEnableSidekickFOMO 0xE34
  FortRuntimeOptions::bEnableSidekickAvatars 0xE35
  FortRuntimeOptions::bSidekickDisablesScreenRecord 0xE36
  FortRuntimeOptions::bSidekickEnableExitFNButton 0xE37
  FortRuntimeOptions::bEnableSidekickFaceAreaInvalidation 0xE38
  FortRuntimeOptions::bSidekickDisabledByNightNight 0xE39
  FortRuntimeOptions::bSidekickForcesSingleChannelMode 0xE3A
  FortRuntimeOptions::bEnableCampaignBatchLevelingUI 0xE3B
  FortRuntimeOptions::bAllowSimultaneousChannelConnections 0xE3C
  FortRuntimeOptions::bExpandNotListeningChannels 0xE3D
  FortRuntimeOptions::MaxSetFriendSubscriptionSettingsAttempts 0xE40
  FortRuntimeOptions::MaxQueryFriendSubscriptionSettingsAttempts 0xE44
  FortRuntimeOptions::NumDaysBetweenPlayingNotifications 0xE48
  FortRuntimeOptions::NumHoursBetweenPlayingNotifications 0xE4C
  FortRuntimeOptions::NumMinutesBetweenPlayingNotifications 0xE50
  FortRuntimeOptions::bForceAutoChangeMaterialOn 0xE54
  FortRuntimeOptions::bActiveDisplayDeviceTemperature 0xE55
  FortRuntimeOptions::bAllowOfflineInvites 0xE56
  FortRuntimeOptions::bEnablePlatformVoiceLeave 0xE57
  FortRuntimeOptions::bEnablePlatformVoicePrompts 0xE58
  FortRuntimeOptions::bEnableVoiceChatEnablePrompt 0xE59
  FortRuntimeOptions::PlaylistGameVoiceChannelRecommendationDisplayTime 0xE5C
  FortRuntimeOptions::bEnablePlaylistGameChannelRecommendationToast 0xE60
  FortRuntimeOptions::bEnableQuickHealing 0xE61
  FortRuntimeOptions::bAllowDeferredPedestalPawnSpawn 0xE62
  FortRuntimeOptions::bRunUnicornOnServer 0xE63
  FortRuntimeOptions::bShowSamsungSensorButtonWarning 0xE64
  FortRuntimeOptions::SamsungSensorButtonGamesPerWarning 0xE68
  FortRuntimeOptions::CatabaExclusiveCountryCodes 0xE70
  FortRuntimeOptions::bEnableItemShopDynamicBackground 0xE80
  FortRuntimeOptions::EnableCommunityVotingScreen 0xE81
  FortRuntimeOptions::CommunityVotingTutorialVersion 0xE84
  FortRuntimeOptions::CommunityVotingRevealDelay 0xE88
  FortRuntimeOptions::CommunityVotingTimerRefreshDelay 0xE8C
  FortRuntimeOptions::ScrollToWinnerTileAfterReveal 0xE90
  FortRuntimeOptions::EnableStandaloneStorefront 0xE91
  FortRuntimeOptions::bEnableBattlePassStorefront 0xE92
  FortRuntimeOptions::bEnableItemPreviewInStore 0xE93
  FortRuntimeOptions::bEnableCurrencyInspectScreenBonusText 0xE94
  FortRuntimeOptions::bEnableCurrencyBonusBanner 0xE95
  FortRuntimeOptions::bEnableItemShopInvalidationBox 0xE96
  FortRuntimeOptions::ScrollToStandaloneSectionOnPopupClosed 0xE97
  FortRuntimeOptions::ItemShopOrdering 0xE98
  FortRuntimeOptions::bEnableItemShopSectionBangs 0xEA8
  FortRuntimeOptions::bEnableItemShopCommunityVotingSectionBang 0xEA9
  FortRuntimeOptions::ItemShopDefaultLandingPriority 0xEB0
  FortRuntimeOptions::ItemShopOverrideDisplayDataList 0xEC0
  FortRuntimeOptions::ItemShopDefaultLanding 0xED0
  FortRuntimeOptions::ItemShopOfferSeenThreshold 0xED4
  FortRuntimeOptions::CommunityVotingTileAnimated 0xED8
  FortRuntimeOptions::ScrollToComTileOnEventPopupClosed 0xED9
  FortRuntimeOptions::EnableThanksVotingPopup 0xEDA
  FortRuntimeOptions::bUseItemPresentationScreenOnItemPurchased 0xEDB
  FortRuntimeOptions::CommunityVotingThanksPopupDelay 0xEDC
  FortRuntimeOptions::ReloadMtxExclusiveCountryCodes 0xEE0
  FortRuntimeOptions::bEnableReloadMtx 0xEF0
  FortRuntimeOptions::bEnableDynamicReloadMtx 0xEF1
  FortRuntimeOptions::bEnableInGameReloadMtx 0xEF2
  FortRuntimeOptions::bEnableCrew 0xEF3
  FortRuntimeOptions::bEnableSubscriptionInspectScreen 0xEF4
  FortRuntimeOptions::bEnableBattlePassViolatorEarnedCurrency 0xEF5
  FortRuntimeOptions::InGameCosmeticItemBangRefreshRate 0xEF8
  FortRuntimeOptions::bUseContentPatchingRestartFlow 0xEFC
  FortRuntimeOptions::bAthenaAutoPickupStackables 0xEFD
  FortRuntimeOptions::ScheduledNotifications 0xF00
  FortRuntimeOptions::bEnableUnicornHighlightsOnClient 0xF10
  FortRuntimeOptions::bEnableHighlightsPromptInCompeteScreen 0xF11
  FortRuntimeOptions::bUseReturnToKairosLoadingScreen 0xF12
  FortRuntimeOptions::bForceReturnToKairosLoadingScreen 0xF13
  FortRuntimeOptions::bDebugForceLoginRelaunch 0xF14
  FortRuntimeOptions::bEnableDADUpdateCheckOnRTMM 0xF15
  FortRuntimeOptions::bShouldAllowNightNightMode 0xF16
  FortRuntimeOptions::NightNightPluginName 0xF18
  FortRuntimeOptions::NightNightCalendarEventName 0xF28
  FortRuntimeOptions::bEnableFrontendMeshRockyRidgeCheck 0xF38
  FortRuntimeOptions::bForceAllowFrontendMeshRockyRidgeCheck 0xF39
  FortRuntimeOptions::FrontendMeshRockyRidgeMetadataKey 0xF40
  FortRuntimeOptions::FrontendMeshRockyRidgeCanaryKey 0xF50
  FortRuntimeOptions::FrontendMeshRockyRidgeInitialIntervalSeconds 0xF60
  FortRuntimeOptions::FrontendMeshRockyRidgeFailureMultiplier 0xF64
  FortRuntimeOptions::FrontendMeshRockyRidgeMaxIntervalSeconds 0xF68
  FortRuntimeOptions::FrontendMeshRockyRidgeMeshName 0xF6C
  FortRuntimeOptions::bForceEverybodyToGoNightNight 0xF74
  FortRuntimeOptions::bQueryKeychainBeforeGoingNightNight 0xF75
  FortRuntimeOptions::bSkipSubGameDuringNightNight 0xF76
  FortRuntimeOptions::bAllowCampaignFrontendToGoNightNight 0xF77
  FortRuntimeOptions::bShouldAllowForcedIntro 0xF78
  FortRuntimeOptions::ForcedIntroName 0xF7C
  FortRuntimeOptions::bShowMovieInGameplayIntro 0xF84
  FortRuntimeOptions::bSkipSubgameSelectDuringForcedIntro 0xF85
  FortRuntimeOptions::bSkipToEndGameplayIntroOutroVideos 0xF86
  FortRuntimeOptions::MaxGameplayCinematicLength 0xF88
  FortRuntimeOptions::bUseAthenaArmory 0xF8C
  FortRuntimeOptions::bEnableLiveSpectateButton 0xF8D
  FortRuntimeOptions::bEnableGuidedTutorialDefensiveBuilding 0xF8E
  FortRuntimeOptions::bEnableSafeZoneEditor 0xF8F
  FortRuntimeOptions::bEnableSavedLoadouts 0xF90
  FortRuntimeOptions::bSavedLoadoutsUseGodTile 0xF91
  FortRuntimeOptions::bEnableSafeZoneEditorOnLogin 0xF92
  FortRuntimeOptions::bEnableSafeZoneEditorWhenNotInApolloIntro 0xF93
  FortRuntimeOptions::LoginFlowCMSRefreshWaitTime 0xF94
  FortRuntimeOptions::bEnableAppResumeCMSUpdate 0xF98
  FortRuntimeOptions::bEnableMOTDAnalytics 0xF99
  FortRuntimeOptions::bEnableTabTransitionMOTDAnalyticsEvent 0xF9A
  FortRuntimeOptions::bAllowStoreSkipOpenAnimation 0xF9B
  FortRuntimeOptions::bAllowInGameStore 0xF9C
  FortRuntimeOptions::bPostGameStoreNoLeto 0xF9D
  FortRuntimeOptions::bPostGameStoreTriggerIncrementalGC 0xF9E
  FortRuntimeOptions::bAllowInGameLocker 0xF9F
  FortRuntimeOptions::bAllowInGameCareer 0xFA0
  FortRuntimeOptions::bAllowInGameActivityBrowser 0xFA1
  FortRuntimeOptions::bEnableGuidedTutorialDirectFlush 0xFA2
  FortRuntimeOptions::bEnableGuidedTutorialABTesting 0xFA3
  FortRuntimeOptions::bEnableHighlightPlayButtonABTesting 0xFA4
  FortRuntimeOptions::bEnableSkipGuidedTutorialABTesting 0xFA5
  FortRuntimeOptions::MaxFrontendFlowStatQueries 0xFA8
  FortRuntimeOptions::ApolloIntroShowMovie 0xFAC
  FortRuntimeOptions::bRunDeimosSpawnTimelines 0xFAD
  FortRuntimeOptions::TeamToPlaceMeshNetPawnsOn 0xFB0
  FortRuntimeOptions::bEnableAddFriendUserSearchDarkTraffic 0xFB4
  FortRuntimeOptions::bEnableExtendedUserSearchUI 0xFB5
  FortRuntimeOptions::bEnableRecursiveMatchAssignmentSearchForTeam 0xFB6
  FortRuntimeOptions::bEnableBackfillCheckForHighestTeamScore 0xFB7
  FortRuntimeOptions::bEnableBackfillCheckForTeamScoreDifference 0xFB8
  FortRuntimeOptions::BackfillCheckForHighestTeamScorePlaylistOverrides 0xFC0
  FortRuntimeOptions::BackfillCheckForScoreDiscrepancyPlaylistOverrides 0x1010
  FortRuntimeOptions::bDisableTdmBackfilledPlayerTeleport 0x1060
  FortRuntimeOptions::bDisableWarmupRequiredPlayerCountCheck 0x1061
  FortRuntimeOptions::bAIDirectorTreatBotsAsPlayersForLOD 0x1062
  FortRuntimeOptions::bEnablePhoenix 0x1063
  FortRuntimeOptions::bBuildingPossessionShown 0x1064
  FortRuntimeOptions::LoadingContentModalWidget 0x1068
  FortRuntimeOptions::bBacchusFrontendEnabled 0x1080
  FortRuntimeOptions::InvalidCreativeItemTags 0x1088
  FortRuntimeOptions::bEnableAFortPlayerPawnOnRep_InVehicleAndUFortVehicleSeatComponentOnRep_PlayerSlotsRaceConditionFix 0x1098
  FortRuntimeOptions::ValkyrieMajMinPatchQueryParams 0x10A0
  FortRuntimeOptions::bSprintingStrafeSnapEnabled 0x10B0
  FortRuntimeOptions::bExplicitSprintableInputRange 0x10B1
  FortRuntimeOptions::MinForwardForSprint 0x10B4
  FortRuntimeOptions::MinForwardForSprintSnapping 0x10B8
  FortRuntimeOptions::AccelerationStrafeMultiplierSprintOverride 0x10BC
  FortRuntimeOptions::KeyboardDiagonalSprintForwardOverride 0x10C0
  FortRuntimeOptions::KeyboardSprintInputWindUpTime 0x10C4
  FortRuntimeOptions::KeyboardMoveInputWindUpTime 0x10C8
  FortRuntimeOptions::bEnableWebAuthFNMobileOnClassicBuild 0x10CC
  FortRuntimeOptions::bPortraitWebAuthFNMobileOnClassicBuild 0x10CD
  FortRuntimeOptions::bBacchusFrontendLabelShown 0x10CE
  FortRuntimeOptions::NoWeaponZoneMaxDestroyCount 0x10D0
  FortRuntimeOptions::NoWeaponZoneResetDestroyCountRate 0x10D4
  FortRuntimeOptions::bAllowCurieIfCreativeOrPlayground 0x10D8
  FortRuntimeOptions::bEnableServerSendPlayerInteractions 0x10D9
  FortRuntimeOptions::ServerSendPlayerInteractionsIntervalSeconds 0x10DC
  FortRuntimeOptions::bEnableServerSendPlayerInteractionsRankInCreativeMode 0x10E0
  FortRuntimeOptions::bEnableServerPlayerInteractionIdleTracking 0x10E1
  FortRuntimeOptions::bEnableNonFriendSquadInteractionTracking 0x10E2
  FortRuntimeOptions::MinInteractionDurationForDispatch 0x10E8
  FortRuntimeOptions::DefaultMissionGen 0x10F0
  FortRuntimeOptions::bGyroV2Enabled 0x1118
  FortRuntimeOptions::bFlickStickEnabled 0x1119
  FortRuntimeOptions::GyroAimAssistMode 0x111C
  FortRuntimeOptions::bForceMotionControlsEnabled 0x1120
  FortRuntimeOptions::bEnableBacchusDialogSystem 0x1121
  FortRuntimeOptions::bBacchusDialogSystemSkipConfirmationStep 0x1122
  FortRuntimeOptions::bMobileDisableResolutionReset 0x1123
  FortRuntimeOptions::bMotionAxisMobileDefaultToYaw 0x1124
  FortRuntimeOptions::bFollowCameraOptionAvailable 0x1125
  FortRuntimeOptions::bAutoCenterOptionAvailable 0x1126
  FortRuntimeOptions::bShouldRestartCreativeServersForCalendarEventChanges 0x1127
  FortRuntimeOptions::bCreativeEmoteControllerUseWhitelist 0x1128
  FortRuntimeOptions::CreativeEmoteControllerWhitelist 0x1130
  FortRuntimeOptions::bPreventLateJoiningPlayersAfterAircraft 0x1140
  FortRuntimeOptions::AllowedPMRStatuses 0x1148

  FortSKPushVehicleConfigs
  FortSKPushVehicleConfigs::PedalForceMultiplier 0x600
  FortSKPushVehicleConfigs::PedalTopSpeedMultiplier 0x604
  FortSKPushVehicleConfigs::PedalForceDuration 0x608
  FortSKPushVehicleConfigs::CoastBrakingMinDelta 0x60C
  FortSKPushVehicleConfigs::CoastBrakingMaxDelta 0x610
  FortSKPushVehicleConfigs::PedalMinDuration 0x614
  FortSKPushVehicleConfigs::MountDuration 0x618
  FortSKPushVehicleConfigs::DismountDuration 0x61C
  FortSKPushVehicleConfigs::MinPreDismountCooldown 0x620
  FortSKPushVehicleConfigs::PreDismountCooldown 0x624
  FortSKPushVehicleConfigs::PedalCooldown 0x628
  FortSKPushVehicleConfigs::CoastBrakingStrength 0x62C
  FortSKPushVehicleConfigs::ShoppingMinPedalCoastSpeed 0x630
  FortSKPushVehicleConfigs::VehicleDebugStrafeCoastMultiplier 0x634
  FortSKPushVehicleConfigs::CanCoastCooldown 0x638
  FortSKPushVehicleConfigs::MaxAutoDismountForwardSpeed 0x63C
  FortSKPushVehicleConfigs::PedalMinForwardVelocity 0x640
  FortSKPushVehicleConfigs::FastDismountDuration 0x644
  FortSKPushVehicleConfigs::CanCoastAfterFastDismountCooldown 0x648
  FortSKPushVehicleConfigs::PassengerVehicleWeightShiftYawStrength 0x64C
  FortSKPushVehicleConfigs::MinPushForceMagnitude 0x650
  FortSKPushVehicleConfigs::MinGearRampTime 0x654

  FortSpaghettiVehicle
  FortSpaghettiVehicle::CacheDriverCameraShake 0x1620
  FortSpaghettiVehicle::BounceContactRepulsionForce 0x1628
  FortSpaghettiVehicle::BoostForce 0x162C
  FortSpaghettiVehicle::MaxVerticalBoostForce 0x1630
  FortSpaghettiVehicle::BoostSpeedKmh 0x1634
  FortSpaghettiVehicle::BaseSphericalDriveParams 0x1638
  FortSpaghettiVehicle::BaseTowhookParams 0x1680
  FortSpaghettiVehicle::TowhookSpringDeformationRateOnGround 0x1750
  FortSpaghettiVehicle::bAutoRetractGrapple 0x1754
  FortSpaghettiVehicle::bCanHoldGrapple 0x1755
  FortSpaghettiVehicle::TowhookInterpSpeed 0x1758
  FortSpaghettiVehicle::TowhookInterpMaxPercentPerSecond 0x175C
  FortSpaghettiVehicle::TowhookMaxInvalidateTargetAngleDeg 0x1760
  FortSpaghettiVehicle::TowhookMaxInvalidateTargetDot 0x1764
  FortSpaghettiVehicle::InternalBlockerCollisionName 0x1768
  FortSpaghettiVehicle::BoostBounceAction 0x1770
  FortSpaghettiVehicle::ProjectileTraceChannel 0x184C
  FortSpaghettiVehicle::ProjectileSpeedKmh 0x1850
  FortSpaghettiVehicle::OnTowhookShot 0x1858
  FortSpaghettiVehicle::OnTowhookAttached 0x1868
  FortSpaghettiVehicle::OnTowhookDetached 0x1878
  FortSpaghettiVehicle::OnTowhookMissed 0x1888
  FortSpaghettiVehicle::OnTowhookHolstered 0x1898
  FortSpaghettiVehicle::OnTowhookYanked 0x18A8
  FortSpaghettiVehicle::OnExtendToggled 0x18B8
  FortSpaghettiVehicle::ReplicatedAttachState 0x18C8
  FortSpaghettiVehicle::FortSpaghettiVehicleConfigs 0x1908
  FortSpaghettiVehicle::NetTowhookAimDir 0x1E90
  FortSpaghettiVehicle::CacheCoilIdleTopR 0x1EB0
  FortSpaghettiVehicle::CacheCoilIdleTopL 0x1EB8
  FortSpaghettiVehicle::CacheCoilIdleBottomR 0x1EC0
  FortSpaghettiVehicle::CacheCoilIdleBottomL 0x1EC8
  FortSpaghettiVehicle::CacheBoostFX 0x1ED0
  FortSpaghettiVehicle::CacheDustFX 0x1ED8
  FortSpaghettiVehicle::CacheAudioMovement 0x1EE0
  FortSpaghettiVehicle::CacheAudioWind 0x1EE8
  FortSpaghettiVehicle::CacheAudioTowCable 0x1EF0

  FortVehicleSeatWeaponComponent
  FortVehicleSeatWeaponComponent::MuzzleSocketNames 0xB0
  FortVehicleSeatWeaponComponent::WeaponSeatDefinitions 0xC0
  FortVehicleSeatWeaponComponent::ActiveSeatIdx 0xD0
  FortVehicleSeatWeaponComponent::CachedWeapon 0xD8
  FortVehicleSeatWeaponComponent::CachedWeaponDef 0xE0
  FortVehicleSeatWeaponComponent::CachedOverheatMax 0xE8
  FortVehicleSeatWeaponComponent::CachedOverheatValue 0xEC
  FortVehicleSeatWeaponComponent::OverheatValueRepped 0xF0
  FortVehicleSeatWeaponComponent::bWeaponEquipped 0xF4
  FortVehicleSeatWeaponComponent::bUseVehicleOrientationForShootingCone 0xF5
  FortVehicleSeatWeaponComponent::bControlledByMultipleSeats 0xF6
  FortVehicleSeatWeaponComponent::bUseWeaponCameraMode 0xF7
  FortVehicleSeatWeaponComponent::ActorBase 0xF8
  FortVehicleSeatWeaponComponent::bReadyToSleep 0x100
  FortVehicleSeatWeaponComponent::TotalShotsAllowedThenShutdown 0x108
  FortVehicleSeatWeaponComponent::ShotsFired 0x130
  FortVehicleSeatWeaponComponent::OnOverheatStateChanged 0x138
  FortVehicleSeatWeaponComponent::bWeaponOverheatDataHasBeenCached 0x148
  FortVehicleSeatWeaponComponent::CachedWeaponOverheatData 0x14C
  FortVehicleSeatWeaponComponent::CachedWeaponState 0x164
  FortVehicleSeatWeaponComponent::bSaveAndRestoreWeaponData 0x170
  FortVehicleSeatWeaponComponent::WeaponSklMeshComponent 0x178
  FortVehicleSeatWeaponComponent::VehicleSocketName 0x180
  FortVehicleSeatWeaponComponent::VehiclePawnAttachSocketName 0x188
  FortVehicleSeatWeaponComponent::AttachmentAngleOffsetYaw 0x190

  FortVehicleAimingWeaponComp
  FortVehicleAimingWeaponComp::bShouldResetCameraHorizontallyToBarrelWhenEntered 0x1A8
  FortVehicleAimingWeaponComp::bShouldResetCameraVerticallyToBarrelWhenEntered 0x1A9
  FortVehicleAimingWeaponComp::StartCameraResetToBarrelTime 0x1AC
  FortVehicleAimingWeaponComp::bAllowCameraLocalVerticalRotationOnly 0x1B0
  FortVehicleAimingWeaponComp::AimBlendInSpeed 0x1B4
  FortVehicleAimingWeaponComp::AimBlendOutSpeed 0x1B8
  FortVehicleAimingWeaponComp::bSetDesiredPitchWhenUnmanned 0x1BC
  FortVehicleAimingWeaponComp::bSetDesiredYawWhenUnmanned 0x1BD
  FortVehicleAimingWeaponComp::bUseGlobalOnlyAiming 0x1BE
  FortVehicleAimingWeaponComp::LocalAimOffsetWhenPitchedUp 0x1C0
  FortVehicleAimingWeaponComp::LocalAimOffsetWhenPitchedFlat 0x1CC
  FortVehicleAimingWeaponComp::LocalAimOffsetWhenPitchedDown 0x1D8
  FortVehicleAimingWeaponComp::RotCyclesPerFullTurnHoriz 0x1E4
  FortVehicleAimingWeaponComp::RotCyclesPerFullTurnVert 0x1E8
  FortVehicleAimingWeaponComp::bCorrectAimFromCameraToMuzzle 0x1EC
  FortVehicleAimingWeaponComp::bUseClientMuzzleLocationAuthority 0x1ED
  FortVehicleAimingWeaponComp::YawDiffRemaining 0x1F0
  FortVehicleAimingWeaponComp::PitchDiffRemaining 0x1F4
  FortVehicleAimingWeaponComp::bInterpolateAimToDesired 0x1F8
  FortVehicleAimingWeaponComp::LastTickTime 0x1FC
  FortVehicleAimingWeaponComp::TickCount 0x200
  FortVehicleAimingWeaponComp::CameraAimBlendFactor 0x204
  FortVehicleAimingWeaponComp::TargetLocalAimOrientation 0x208
  FortVehicleAimingWeaponComp::TargetLocalAimOrientationCorrected 0x214
  FortVehicleAimingWeaponComp::CurrentLocalAimOrientation 0x220
  FortVehicleAimingWeaponComp::CurrentLocalAimOrientationCorrected 0x22C
  FortVehicleAimingWeaponComp::TargetLocalAimOrientationRepped 0x238
  FortVehicleAimingWeaponComp::TargetLocalAimOrientationCorrectedRepped 0x244
  FortVehicleAimingWeaponComp::UnmannedDesiredPitch 0x250
  FortVehicleAimingWeaponComp::UnmannedDesiredYaw 0x254
  FortVehicleAimingWeaponComp::HorizAimRotDelta 0x258
  FortVehicleAimingWeaponComp::VertAimRotDelta 0x25C
  FortVehicleAimingWeaponComp::AimSourceType 0x260
  FortVehicleAimingWeaponComp::bPlayerEnteredThisFrame 0x261
  FortVehicleAimingWeaponComp::bApplyOwnerRotationToAimWhenUnmanned 0x262
  FortVehicleAimingWeaponComp::MaxYawPerSecondThreshold 0x264
  FortVehicleAimingWeaponComp::MaxPitchPerSecondThreshold 0x268
  FortVehicleAimingWeaponComp::PitchConstraintAngleOffset 0x26C
  FortVehicleAimingWeaponComp::AimInterpSpeed 0x270
  FortVehicleAimingWeaponComp::InitialCameraInterpSpeed 0x274
  FortVehicleAimingWeaponComp::InitialCameraLerpTime 0x278
  FortVehicleAimingWeaponComp::MinDistanceForCorrection 0x27C
  FortVehicleAimingWeaponComp::AnimatedMuzzleLocation 0x280

  FortVehicleFuelComponent
  FortVehicleFuelComponent::OnFuelChanged 0xB0
  FortVehicleFuelComponent::OnRefueledFromEmpty 0xC0
  FortVehicleFuelComponent::OnOutOfFuel 0xD0
  FortVehicleFuelComponent::OnLowFuel 0xE0
  FortVehicleFuelComponent::OwnerVehicle 0xF0
  FortVehicleFuelComponent::ServerFuel 0xF8
  FortVehicleFuelComponent::OutOfFuelSound 0x100
  FortVehicleFuelComponent::LowFuelSound 0x108
  FortVehicleFuelComponent::LowFuelRepeatingPing 0x110
  FortVehicleFuelComponent::UsesFuelSystem 0x118
  FortVehicleFuelComponent::InitializeWithStartingFuel 0x140
  FortVehicleFuelComponent::FuelTankCapacity 0x168
  FortVehicleFuelComponent::FuelPerSecondIdle 0x190
  FortVehicleFuelComponent::FuelPerSecondDriving 0x1B8
  FortVehicleFuelComponent::FuelPerSecondBoosting 0x1E0
  FortVehicleFuelComponent::MinFuelAtSpawn 0x218
  FortVehicleFuelComponent::MaxFuelAtSpawn 0x240
  FortVehicleFuelComponent::InfiniteFuel 0x268
  FortVehicleFuelComponent::LowFuelRepeatingPingDelay 0x290
  FortVehicleFuelComponent::LowFuelPercent 0x2B8
  FortVehicleFuelComponent::CustomFuelUI 0x2E0

  FortVehicleItemDefinition
  FortVehicleItemDefinition::VehicleMinSpawnPercent 0x830
  FortVehicleItemDefinition::VehicleMaxSpawnPercent 0x858
  FortVehicleItemDefinition::MaxNumberCanSpawn 0x880
  FortVehicleItemDefinition::MinPercentWithGas 0x8A8
  FortVehicleItemDefinition::MaxPercentWithGas 0x8D0
  FortVehicleItemDefinition::MinPercentInoperable 0x8F8
  FortVehicleItemDefinition::MaxPercentInoperable 0x920
  FortVehicleItemDefinition::WrapPreviewTransform 0x950
  FortVehicleItemDefinition::WrapPreviewSectionMask 0x980
  FortVehicleItemDefinition::bUseInWrapPreviewList 0x984
  FortVehicleItemDefinition::VehicleActorClass 0x988
  FortVehicleItemDefinition::PreviewSkeletalMesh 0x9B0
  FortVehicleItemDefinition::SpawnVehicleNames 0x9D8
  FortVehicleItemDefinition::MaxSpawnDistance 0x9E8

  FortVehicleManager
  FortVehicleManager::OnVehicleCountByTagChanged 0x230
  FortVehicleManager::Vehicles 0x248
  FortVehicleManager::VehicleCountByTagMap 0x278

  FortVehicleMovementSet
  FortVehicleMovementSet::FrontLateralFrictionScale 0x30
  FortVehicleMovementSet::RearLateralFrictionScale 0x58
  FortVehicleMovementSet::BrakeForceTractionScale 0x80
  FortVehicleMovementSet::ForwardForceTractionScale 0xA8
  FortVehicleMovementSet::SlopeAntigravityScale 0xD0
  FortVehicleMovementSet::TopSpeedScale 0xF8
  FortVehicleMovementSet::VehicleGravityScale 0x120

  FortWeakPoint
  FortWeakPoint::OnWeakPointStateChangedDelegate 0x8D8
  FortWeakPoint::CachedWeakPointCoordinator 0x8E8
  FortWeakPoint::WeakPointState 0x8F0
  FortWeakPoint::WeakPointAttachmentSocketName 0x8F4
  FortWeakPoint::bShouldDisplayHealthBarWhenActive 0x8FC
  FortWeakPoint::bShouldRegisterForAimAssist 0x8FD

  FortWeaponAttrSet
  FortWeaponAttrSet::WeaponChanceToNotConsumeAmmo 0x30
  FortWeaponAttrSet::AccumulatedWeaponChanceToNotConsumeAmmo 0x58
  FortWeaponAttrSet::WeaponRateOfFire 0x80
  FortWeaponAttrSet::WeaponHorizontalRecoil 0xA8
  FortWeaponAttrSet::WeaponVerticalRecoil 0xD0
  FortWeaponAttrSet::WeaponSpreadReduction 0xF8
  FortWeaponAttrSet::WeaponReloadSpeed 0x120
  FortWeaponAttrSet::WeaponAmmoClipSize 0x148
  FortWeaponAttrSet::WeaponChargeRate 0x170
  FortWeaponAttrSet::WeaponOverheatMultiplier 0x198
  FortWeaponAttrSet::WeaponOverheatMaxMultiplier 0x1C0
  FortWeaponAttrSet::WeaponOverheatCoolingMultiplier 0x1E8
  FortWeaponAttrSet::WeaponOverheatCooldownMultiplier 0x210
  FortWeaponAttrSet::CharacterItemDurabilityDecayModifier 0x238

  FortWeaponPickaxeAthena
  FortWeaponPickaxeAthena::SwingVFX 0x1488
  FortWeaponPickaxeAthena::IdleVFX 0x1490
  FortWeaponPickaxeAthena::AnimTrailsPSC 0x1498
  FortWeaponPickaxeAthena::AnimTrailsPSCTemplate 0x14A0
  FortWeaponPickaxeAthena::AnimTrailsNiagaraAsset 0x14A8
  FortWeaponPickaxeAthena::bUseAnimTrailsPSC 0x14B0
  FortWeaponPickaxeAthena::AnimTrailsFirstSocketName 0x14B4
  FortWeaponPickaxeAthena::AnimTrailsSecondSocketName 0x14BC
  FortWeaponPickaxeAthena::AnimTrailsWidth 0x14C4
  FortWeaponPickaxeAthena::IdleFXSocketName 0x14C8
  FortWeaponPickaxeAthena::SwingFXSocketName 0x14D0
  FortWeaponPickaxeAthena::GenericImpactSound 0x14D8
  FortWeaponPickaxeAthena::Material0MID 0x14E0
  FortWeaponPickaxeAthena::bWatchKills 0x14E8
  FortWeaponPickaxeAthena::WatchedKills 0x14EC
  FortWeaponPickaxeAthena::bCandyCaneKillReaction 0x14F0
  FortWeaponPickaxeAthena::CQCEnemyAudio 0x14F8
  FortWeaponPickaxeAthena::PokeAnimationsToCheckForOnImpact 0x1500
  FortWeaponPickaxeAthena::PickaxeHarvestingMontage 0x1510
  FortWeaponPickaxeAthena::CachedCosmeticItemDefinition 0x1518
  FortWeaponPickaxeAthena::SoftFallbackMesh 0x1528
  FortWeaponPickaxeAthena::LoadedFallbackMesh 0x1550
  FortWeaponPickaxeAthena::CosmeticData 0x1558

  FortWeaponRanged
  FortWeaponRanged::OnProjectileSpawned 0x1488
  FortWeaponRanged::TracerTemplate 0x14B0
  FortWeaponRanged::bAllowAutomaticWeaponCatchup 0x14B8
  FortWeaponRanged::CurrentNumBullets 0x14C0
  FortWeaponRanged::ScopeTargetingMuzzleOffset 0x14C4
  FortWeaponRanged::CurrentMuzzleBlockedLocation 0x14D0
  FortWeaponRanged::CurrentDamageStart 0x14DC
  FortWeaponRanged::MaxTargetingAimAdjustment 0x14E0
  FortWeaponRanged::bShouldDisplayAmmoCounter 0x14EC
  FortWeaponRanged::bShouldDisplayAmmoCounterDuringSecondaryFire 0x14EC
  FortWeaponRanged::bShouldHideReserveAmmo 0x14EC
  FortWeaponRanged::bShouldAimFromMuzzleAtCloseRange 0x14EC
  FortWeaponRanged::bAlwaysAimFromMuzzle 0x14EC
  FortWeaponRanged::bMaintainAimLocationDuringTargeting 0x14EC
  FortWeaponRanged::bUseScopeTargeting 0x14EC
  FortWeaponRanged::bUseFirstPersonTargeting 0x14EC
  FortWeaponRanged::bPersistentFireFX 0x14ED
  FortWeaponRanged::bUseBeamParticles 0x14ED
  FortWeaponRanged::bActivateRangeAbilityPerBurstShot 0x14ED
  FortWeaponRanged::bUseImpactFXForProjectiles 0x14ED
  FortWeaponRanged::bUseImpactFXForProjectileOverlaps 0x14ED
  FortWeaponRanged::bUseImpactDecals 0x14ED
  FortWeaponRanged::bUsePersistentBeam 0x14ED
  FortWeaponRanged::bUseShellsParticles 0x14ED
  FortWeaponRanged::bUseTracers 0x14EE
  FortWeaponRanged::bUseOverrideBaseSpread 0x14EE
  FortWeaponRanged::bIsMuzzleTraceNearWall 0x14EE
  FortWeaponRanged::MuzzleTraceNearWallThreshold 0x14F0
  FortWeaponRanged::BeamSignificance 0x1500
  FortWeaponRanged::ImpactSignificance 0x1518
  FortWeaponRanged::DecalSignificance 0x1530
  FortWeaponRanged::ScopeImpactEffectDistanceOffset 0x1548
  FortWeaponRanged::MuzzlePSC 0x1550
  FortWeaponRanged::ShellPSC 0x1558
  FortWeaponRanged::BeamParticleSystem 0x1560
  FortWeaponRanged::BeamNiagaraSystemAsset 0x1568
  FortWeaponRanged::BeamSourceSocketName 0x1590
  FortWeaponRanged::FortSpawnPropOverride 0x1598
  FortWeaponRanged::FortSpawnPropAnimOverride 0x15A0
  FortWeaponRanged::DecalSizeMin 0x15A8
  FortWeaponRanged::DecalSizeMax 0x15B4
  FortWeaponRanged::DecalLifespanMin 0x15C0
  FortWeaponRanged::DecalLifespanMax 0x15C4
  FortWeaponRanged::DecalColorStart 0x15C8
  FortWeaponRanged::DecalColorEnd 0x15D8
  FortWeaponRanged::DecalMaterial 0x15E8
  FortWeaponRanged::DecalTexture 0x15F0
  FortWeaponRanged::SurfaceAcceptingDecals 0x15F8
  FortWeaponRanged::ShellReloadCounter 0x160C
  FortWeaponRanged::TargetingRotAdjustmentTotal 0x1614
  FortWeaponRanged::LastTargetingRotAdjustmentWeight 0x1620
  FortWeaponRanged::ScopePostProcessEnabled 0x1670
  FortWeaponRanged::ScopePostProcessBlendWeight 0x1674
  FortWeaponRanged::ScopePostProcessMaterial 0x1678
  FortWeaponRanged::BulletPattern 0x1690
  FortWeaponRanged::BeamNiagaraSystemInstance 0x16D0
  FortWeaponRanged::bUseAthenaRecoil 0x1734
  FortWeaponRanged::bUseAthenaPerfectADSAim 0x1734
  FortWeaponRanged::bFirstShotAccuracyCheckVehicleMovement 0x1734
  FortWeaponRanged::FirstShotAccuracyMinWaitTime 0x1738
  FortWeaponRanged::BulletCountForPerBulletRecoil 0x173C
  FortWeaponRanged::FireAnimation 0x1770
  FortWeaponRanged::FireDownsightsAnimation 0x1778
  FortWeaponRanged::FireFromCrouchWalkAnimation 0x1780
  FortWeaponRanged::CockingAnimation 0x1788
  FortWeaponRanged::WeaponFireMontage 0x1790
  FortWeaponRanged::WeaponFireDownsightsMontage 0x1798
  FortWeaponRanged::WeaponFireFromCrouchWalkMontage 0x17A0
  FortWeaponRanged::WeaponCockingMontage 0x17A8
  FortWeaponRanged::BeamPSC 0x17B0
  FortWeaponRanged::CrouchWalkSpeedThreshold 0x17B8
  FortWeaponRanged::bEnableRecoilDelay 0x17BC
  FortWeaponRanged::OnOverheatValueChanged 0x17E0
  FortWeaponRanged::OverheatState 0x17F0
  FortWeaponRanged::OverheatedAnimation 0x17F8
  FortWeaponRanged::WeaponOverheatedAnimation 0x1800
  FortWeaponRanged::bCooldownWhileOverheated 0x1808
  FortWeaponRanged::OverheatValue 0x180C
  FortWeaponRanged::TimeHeatWasLastAdded 0x1814
  FortWeaponRanged::TimeOverheatedBegan 0x1818
  FortWeaponRanged::bCacheAimPointOnFire 0x181C
  FortWeaponRanged::CachedAimPoint 0x1820
  FortWeaponRanged::CachedLODSettingsManager 0x1840

  WorldSettings
  WorldSettings::VisibilityCellSize 0x228
  WorldSettings::VisibilityAggressiveness 0x22C
  WorldSettings::bPrecomputeVisibility 0x22D
  WorldSettings::bPlaceCellsOnlyAlongCameraTracks 0x22D
  WorldSettings::bEnableWorldBoundsChecks 0x22D
  WorldSettings::bEnableNavigationSystem 0x22D
  WorldSettings::bEnableAISystem 0x22D
  WorldSettings::bEnableWorldComposition 0x22D
  WorldSettings::bUseClientSideLevelStreamingVolumes 0x22D
  WorldSettings::bEnableWorldOriginRebasing 0x22D
  WorldSettings::bWorldGravitySet 0x22E
  WorldSettings::bGlobalGravitySet 0x22E
  WorldSettings::bMinimizeBSPSections 0x22E
  WorldSettings::bForceNoPrecomputedLighting 0x22E
  WorldSettings::bHighPriorityLoading 0x22E
  WorldSettings::bHighPriorityLoadingLocal 0x22E
  WorldSettings::bOverrideDefaultBroadphaseSettings 0x22E
  WorldSettings::bGenerateSingleClusterForLevel 0x22E
  WorldSettings::AISystemClass 0x230
  WorldSettings::LevelInstancePivotOffset 0x258
  WorldSettings::NavigationSystemConfig 0x268
  WorldSettings::NavigationSystemConfigOverride 0x270
  WorldSettings::WorldPartition 0x278
  WorldSettings::InstancedFoliageGridSize 0x280
  WorldSettings::DefaultPlacementGridSize 0x284
  WorldSettings::WorldToMeters 0x288
  WorldSettings::KillZ 0x28C
  WorldSettings::KillZDamageType 0x290
  WorldSettings::WorldGravityZ 0x298
  WorldSettings::GlobalGravityZ 0x29C
  WorldSettings::DefaultPhysicsVolumeClass 0x2A0
  WorldSettings::PhysicsCollisionHandlerClass 0x2A8
  WorldSettings::DefaultGameMode 0x2B0
  WorldSettings::GameNetworkManagerClass 0x2B8
  WorldSettings::PackedLightAndShadowMapTextureSize 0x2C0
  WorldSettings::DefaultColorScale 0x2C4
  WorldSettings::DefaultMaxDistanceFieldOcclusionDistance 0x2D0
  WorldSettings::GlobalDistanceFieldViewDistance 0x2D4
  WorldSettings::DynamicIndirectShadowsSelfShadowingIntensity 0x2D8
  WorldSettings::DefaultReverbSettings 0x2E0
  WorldSettings::DefaultAmbientZoneSettings 0x300
  WorldSettings::DefaultBaseSoundMix 0x328
  WorldSettings::TimeDilation 0x330
  WorldSettings::MatineeTimeDilation 0x334
  WorldSettings::DemoPlayTimeDilation 0x338
  WorldSettings::MinGlobalTimeDilation 0x33C
  WorldSettings::MaxGlobalTimeDilation 0x340
  WorldSettings::MinUndilatedFrameTime 0x344
  WorldSettings::MaxUndilatedFrameTime 0x348
  WorldSettings::BroadphaseSettings 0x34C
  WorldSettings::ReplicationViewers 0x390
  WorldSettings::AssetUserData 0x3A0
  WorldSettings::PauserPlayerState 0x3B0
  WorldSettings::MaxNumberOfBookmarks 0x3B8
  WorldSettings::DefaultBookmarkClass 0x3C0
  WorldSettings::BookmarkArray 0x3C8
  WorldSettings::LastBookmarkClass 0x3D8

  FortWorldSettings
  FortWorldSettings::ActorsNeedingWorldReady 0x3E0
  FortWorldSettings::WorldCells 0x3F0
  FortWorldSettings::WorldCellsOrigin 0x400
  FortWorldSettings::WorldCellsFlags 0x40C
  FortWorldSettings::bGenerateTestLevelSaves 0x410
  FortWorldSettings::bDisableCullDistance 0x410
  FortWorldSettings::bUseWorldSpecificCullDistanceOverride 0x410
  FortWorldSettings::bPvPUseWidgetRotation 0x410
  FortWorldSettings::bOverrideMainMapSettings 0x410
  FortWorldSettings::bValidateNavGraphConnectivity 0x410
  FortWorldSettings::bLimitNavGraphSkyCells 0x410
  FortWorldSettings::bUseProceduralFoliage 0x410
  FortWorldSettings::bUseConditionalBuildingFoundations 0x411
  FortWorldSettings::bAllowBuildingStreamingData 0x411
  FortWorldSettings::SplineHLODIndex 0x414
  FortWorldSettings::bShowTimeOfDayManager 0x418
  FortWorldSettings::MinCullObjectSize 0x41C
  FortWorldSettings::MinCullDistance 0x420
  FortWorldSettings::MaxCullObjectSize 0x424
  FortWorldSettings::MaxCullDistance 0x428
  FortWorldSettings::OverrideMinimapMaterial 0x430
  FortWorldSettings::PvPMapWorldCenter 0x438
  FortWorldSettings::MapZOffset 0x440
  FortWorldSettings::MapRotation 0x444
  FortWorldSettings::MapInitialMask 0x450
  FortWorldSettings::bSpawnVehicleManager 0x458
  FortWorldSettings::bSpawnPhysicsObjectManager 0x458
  FortWorldSettings::MapWorldScale 0x45C
  FortWorldSettings::MiniMapZoom 0x460
  FortWorldSettings::AircraftPathBrush 0x470
  FortWorldSettings::AircraftMidlinePathBrush 0x520
  FortWorldSettings::AircraftPathTeamIndicatorBrush 0x5D0
  FortWorldSettings::SafeZoneFinalPosBrush 0x680
  FortWorldSettings::NavGraphSkyCells 0x730
  FortWorldSettings::SearchSpeedOverride 0x740
  FortWorldSettings::ResourceRateOverride 0x748
  FortWorldSettings::SoundBodyHeadshotRequired 0x750
  FortWorldSettings::bSpawnTimeOfDayManager 0x758
  FortWorldSettings::bDisableGlobalWeatherEvents 0x758
  FortWorldSettings::WorldTimeOfDayManager 0x760
  FortWorldSettings::WorldMusicManager 0x788
  FortWorldSettings::WorldMusicManagerBank 0x7B0
  FortWorldSettings::DefaultWorldTimeOfDayManager 0x7B8
  FortWorldSettings::ZoneThemeTimeOfDayManager 0x7E0
  FortWorldSettings::MissionTimeOfDayManager 0x808
  FortWorldSettings::ZoneThemeMusicManager 0x830
  FortWorldSettings::ZoneThemeMusicManagerBank 0x858
  FortWorldSettings::BuildingFoundationStreamingData 0x860
  FortWorldSettings::TimeOfDayManager 0x870
  FortWorldSettings::VehicleManager 0x878
  FortWorldSettings::PhysicsObjectManager 0x880
  FortWorldSettings::LevelOverlayManager 0x888

  GameDataBR
  GameDataBR::AnalyticsItemExclusionDataBR 0x30
  GameDataBR::LootTierDataTablesBR 0x58
  GameDataBR::LootPackageDataTablesBR 0x68
  GameDataBR::QuestEventXPTable 0x78
  GameDataBR::QuestEventXPRegistry 0xA0
  GameDataBR::RarityTokens 0xA8
  GameDataBR::NamedWeightTagQueryTable 0xB8
  GameDataBR::AIGoalManagerBR 0xE0
  GameDataBR::AIDirectorBR 0x108
  GameDataBR::DefaultDamageReceiverClassBR 0x130
  GameDataBR::FeedbackManagerClassBR 0x158
  GameDataBR::UIFeedbackBankBR 0x180
  GameDataBR::DefaultHeroBR 0x1A8
  GameDataBR::PlayerAbilitySetBR 0x1D0
  GameDataBR::CompetitiveIdentityDataTable 0x1F8
  GameDataBR::FortItemsForEventMapping 0x220
  GameDataBR::FortItemToPickupBGAMapping 0x248
  GameDataBR::WeaponReticleExtensions 0x270
  GameDataBR::FeedbackEventData 0x298
  GameDataBR::DefaultRebootVanIndicatorClass 0x2C0
  GameDataBR::DefaultContextTutorialIndicatorClass 0x2E8
  GameDataBR::DefaultEliminationIndicatorClass 0x310
  GameDataBR::CreativeInventoryTable 0x338
  GameDataBR::CreativeRealEstatePlotTable 0x360
  GameDataBR::CreativeBetaPermissions 0x388
  GameDataBR::CreativeDynamicXp 0x390
  GameDataBR::CreativePlaysetProps 0x3B8
  GameDataBR::CachedCreativeInventory 0x3E0
  GameDataBR::CachedCreativeRealEstatePlots 0x430
  GameDataBR::CachedCreativeBetaPermissions 0x440
  GameDataBR::CachedCreativePlaysetProps 0x490
  GameDataBR::CreativeTagsTable 0x4E0
  GameDataBR::CreativeTagCategoriesTable 0x508
  GameDataBR::MapPreloadData 0x530
  GameDataBR::FortWeaponPickupSpawnAmmoData 0x558
  GameDataBR::FrontendGameStateComponents 0x580
  GameDataBR::FortFactionMapping 0x590
  GameDataBR::ItemWrapConfigAsset 0x5B8
  GameDataBR::DefaultGliderAnimSet 0x5E0
  GameDataBR::UmbrellaGliderAnimSet 0x608
  GameDataBR::ItemDefToItemVariantDataMappingAsset 0x630
  GameDataBR::WeaponUpgradeTable 0x658
  GameDataBR::DefaultGlobalCurrencyItemDefinition 0x680
  GameDataBR::DefaultCurrencyPayoutTable 0x6A8
  GameDataBR::DefaultLootGroupData 0x6D0
  GameDataBR::PlayerAttributesClampingDataTable 0x6F8
  GameDataBR::BotItemDataTable 0x720
  GameDataBR::BotSupportedItemTags 0x748
  GameDataBR::FallbackSeason 0x768
  GameDataBR::UnableToPerformActionMessages 0x770
  GameDataBR::HUDVisibilityGameplayTags 0x780
  GameDataBR::TimeOfDayRGBForPeripherals 0x790
  GameDataBR::AthenaSoundMix 0x798
  GameDataBR::AthenaReverbEffect 0x7A0
  GameDataBR::AthenaReverbEffectTag 0x7A8
  GameDataBR::VisualizationSoundMix 0x7B0
  GameDataBR::RespawnDataTable 0x7B8
  GameDataBR::NamedWeightsByPoi 0x7C0
  GameDataBR::AthenaMemoryCostRegister 0x7C8

  FortPlayerDBNORevivedParams
  FortPlayerDBNORevivedParams::RevivedPlayer 0x28
  FortPlayerDBNORevivedParams::RevivedBy 0x30

  FortPlayerDBNOEnterParams
  FortPlayerDBNOEnterParams::KilledPlayer 0x28
  FortPlayerDBNOEnterParams::KilledBy 0x30

  FortReleaseVersionManager
  FortReleaseVersionManager::CurrentVersion 0x60
  FortReleaseVersionManager::AllVersions 0x68
