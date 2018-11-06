### 视角函数

###### 鼠标查看是指按住鼠标右键并控制移动方向。这些API不包括通过按住鼠标左键来移动视角。

PROTECTED [CameraOrSelectOrMoveStart](https://wow.gamepedia.com/API_CameraOrSelectOrMoveStart)\(\) - 在3D世界中开始左键点击.

PROTECTED [CameraOrSelectOrMoveStop](https://wow.gamepedia.com/API_CameraOrSelectOrMoveStop)\(\[stickyFlag\]\) - 在3D世界中停止左键点击.

[CameraZoomIn](https://wow.gamepedia.com/API_CameraZoomIn)\(increment\) - 通过增量将镜头放大到视图平面。

[CameraZoomOut](https://wow.gamepedia.com/API_CameraZoomOut)\(increment\) - 通过增量将镜头缩小到视图平面之外。

[FlipCameraYaw](https://wow.gamepedia.com/API_FlipCameraYaw)\(degrees\) - 以Z度指定的角度量以Z度轴旋转镜头。

[GetCameraZoom](https://wow.gamepedia.com/API_GetCameraZoom)\(\) - 返回当前缩放级别，忽略镜头碰撞。

[IsMouselooking](https://wow.gamepedia.com/API_IsMouselooking)\(\) - 如果鼠标查看当前处于活动状态，则返回1，否则返回nil。

[MouselookStart](https://wow.gamepedia.com/API_MouselookStart)\(\) - 进入鼠标查看模式;鼠标移动用于调整移动/面向方向。

[MouselookStop](https://wow.gamepedia.com/API_MouselookStop)\(\) - 退出鼠标查看模式;鼠标移动用于移动鼠标光标。

[MoveViewDownStart](https://wow.gamepedia.com/API_MoveViewDownStart)\(\) - 开始向下旋转镜头。

[MoveViewDownStop](https://wow.gamepedia.com/API_MoveViewDownStop)\(\) - [MoveViewDownStart](https://wow.gamepedia.com/API_MoveViewDownStart)\(\)被调用后停止向下旋转镜头.

[MoveViewInStart](https://wow.gamepedia.com/API_MoveViewInStart)\(\) - 开始缩放镜头。

[MoveViewInStop](https://wow.gamepedia.com/API_MoveViewInStop)\(\) - [MoveViewInStart](https://wow.gamepedia.com/API_MoveViewInStart)\(\) 被调用后停止缩放镜头.

[MoveViewLeftStart](https://wow.gamepedia.com/API_MoveViewLeftStart)\(\) - 开始将镜头向左旋转。

[MoveViewLeftStop](https://wow.gamepedia.com/API_MoveViewLeftStop)\(\) - [MoveViewLeftStart](https://wow.gamepedia.com/API_MoveViewLeftStart)\(\) 被调用后停止向左旋转镜头.

[MoveViewOutStart](https://wow.gamepedia.com/API_MoveViewOutStart)\(\) - 开始缩小镜头。

[MoveViewOutStop](https://wow.gamepedia.com/API_MoveViewOutStop)\(\) - [MoveViewOutStart](https://wow.gamepedia.com/API_MoveViewOutStart)\(\) 被调用后停止缩小镜头.

[MoveViewRightStart](https://wow.gamepedia.com/API_MoveViewRightStart)\(\) - 开始将镜头向右旋转。

[MoveViewRightStop](https://wow.gamepedia.com/API_MoveViewRightStop)\(\) - [MoveViewRightStart](https://wow.gamepedia.com/API_MoveViewRightStart)\(\) 被调用后停止向右旋转.

[MoveViewUpStart](https://wow.gamepedia.com/API_MoveViewUpStart)\(\) - 开始向上旋转镜头。

[MoveViewUpStop](https://wow.gamepedia.com/API_MoveViewUpStop)\(\) - [MoveViewUpStart](https://wow.gamepedia.com/API_MoveViewUpStart)\(\)被调用后停止向上旋转镜头.

PROTECTED PitchDownStart\(\) - 开始向下倾斜镜头。

PROTECTED PitchDownStop\(\) - PitchDownStart\(\) 被调用后停止向下倾斜镜头.

PROTECTED PitchUpStart\(\) - 开始向上倾斜镜头.

PROTECTED PitchUpStop\(\) - PitchUpStart\(\) 被调用后停止向上倾斜镜头.

NextView\(\) - Cycles forward through the five predefined camera positions.

PrevView\(\) - Cycles backward through the five predefined camera positions.

ResetView\(index\) - Resets the specified \(1-5\) predefined camera position to it's default if it was changed using SaveView\(index\).

[SaveView](https://wow.gamepedia.com/API_SaveView)\(index\) - Replaces the specified \(1-5\) predefined camera positions with the current camera position.

[SetView](https://wow.gamepedia.com/API_SetView)\(index\) - Sets camera position to a specified \(1-5\) predefined camera position.

