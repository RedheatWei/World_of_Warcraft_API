### 视角函数

###### 鼠标查看是指按住鼠标右键并控制移动方向。这些API不包括通过按住鼠标左键来移动视角。

PROTECTED [CameraOrSelectOrMoveStart](https://wow.gamepedia.com/API_CameraOrSelectOrMoveStart)\(\) - 在3D世界中开始左键点击.

PROTECTED [CameraOrSelectOrMoveStop](https://wow.gamepedia.com/API_CameraOrSelectOrMoveStop)\(\[stickyFlag\]\) - 在3D世界中停止左键点击.

[CameraZoomIn](https://wow.gamepedia.com/API_CameraZoomIn)\(increment\) - 通过增量将摄像机放大到视图平面。

[CameraZoomOut](https://wow.gamepedia.com/API_CameraZoomOut)\(increment\) - 通过增量将相机缩小到视图平面之外。

[FlipCameraYaw](https://wow.gamepedia.com/API_FlipCameraYaw)\(degrees\) - 以Z度指定的角度量以Z度轴旋转摄像机。

[GetCameraZoom](https://wow.gamepedia.com/API_GetCameraZoom)\(\) - 返回当前缩放级别，忽略相机碰撞。

[IsMouselooking](https://wow.gamepedia.com/API_IsMouselooking)\(\) - 如果mouselook当前处于活动状态，则返回1，否则返回nil。

[MouselookStart](https://wow.gamepedia.com/API_MouselookStart)\(\) - 进入鼠标查看模式;鼠标移动用于调整移动/面向方向。

[MouselookStop](https://wow.gamepedia.com/API_MouselookStop)\(\) - 退出鼠标查看模式;鼠标移动用于移动鼠标光标。

[MoveViewDownStart](https://wow.gamepedia.com/API_MoveViewDownStart)\(\) - Begins rotating the camera downward.

[MoveViewDownStop](https://wow.gamepedia.com/API_MoveViewDownStop)\(\) - Stops rotating the camera after [MoveViewDownStart](https://wow.gamepedia.com/API_MoveViewDownStart)\(\) is called.

[MoveViewInStart](https://wow.gamepedia.com/API_MoveViewInStart)\(\) - Begins zooming the camera in.

[MoveViewInStop](https://wow.gamepedia.com/API_MoveViewInStop)\(\) - Stops zooming the camera in after [MoveViewInStart](https://wow.gamepedia.com/API_MoveViewInStart)\(\) is called.

[MoveViewLeftStart](https://wow.gamepedia.com/API_MoveViewLeftStart)\(\) - Begins rotating the camera to the Left.

[MoveViewLeftStop](https://wow.gamepedia.com/API_MoveViewLeftStop)\(\) - Stops rotating the camera after [MoveViewLeftStart](https://wow.gamepedia.com/API_MoveViewLeftStart)\(\) is called.

[MoveViewOutStart](https://wow.gamepedia.com/API_MoveViewOutStart)\(\) - Begins zooming the camera out.

[MoveViewOutStop](https://wow.gamepedia.com/API_MoveViewOutStop)\(\) - Stops zooming the camera out after [MoveViewOutStart](https://wow.gamepedia.com/API_MoveViewOutStart)\(\) is called.

[MoveViewRightStart](https://wow.gamepedia.com/API_MoveViewRightStart)\(\) - Begins rotating the camera to the Right.

[MoveViewRightStop](https://wow.gamepedia.com/API_MoveViewRightStop)\(\) - Stops rotating the camera after [MoveViewRightStart](https://wow.gamepedia.com/API_MoveViewRightStart)\(\) is called.

[MoveViewUpStart](https://wow.gamepedia.com/API_MoveViewUpStart)\(\) - Begins rotating the camera upward.

[MoveViewUpStop](https://wow.gamepedia.com/API_MoveViewUpStop)\(\) - Stops rotating the camera after [MoveViewUpStart](https://wow.gamepedia.com/API_MoveViewUpStart)\(\) is called.

PROTECTED PitchDownStart\(\) - Begins pitching the camera Downward.

PROTECTED PitchDownStop\(\) - Stops pitching the camera after PitchDownStart\(\) is called.

PROTECTED PitchUpStart\(\) - Begins pitching the camera Upward.

PROTECTED PitchUpStop\(\) - Stops pitching the camera after PitchUpStart\(\) is called.

NextView\(\) - Cycles forward through the five predefined camera positions.

PrevView\(\) - Cycles backward through the five predefined camera positions.

ResetView\(index\) - Resets the specified \(1-5\) predefined camera position to it's default if it was changed using SaveView\(index\).

[SaveView](https://wow.gamepedia.com/API_SaveView)\(index\) - Replaces the specified \(1-5\) predefined camera positions with the current camera position.

[SetView](https://wow.gamepedia.com/API_SetView)\(index\) - Sets camera position to a specified \(1-5\) predefined camera position.

