# 生图提示词模板

每张图单独生成。根据正文内容替换变量，不要把多张图拼在一起。

```text
Generate one standalone 16:9 horizontal Chinese article illustration.

Visual DNA:
Pure white background. Hand-drawn sketch line art style with slightly wobbly pen lines. Lots of empty white space. Sparse red/orange/blue handwritten Chinese annotations. Clean but energetic product-sketch feeling. No gradients, no shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no cute mascot poster, no children's illustration, no realistic UI.

Recurring IP character required:
小悟空 (young Son Goku from Dragon Ball, child version): iconic black spiky hair pointing upward in all directions, large expressive eyes, small nose, round cheeks, determined and energetic but serious expression. Wearing a white sleeveless tank top, baggy blue bloomers tied with a light blue sash, red wristbands, dark blue flat shoes. A red staff (如意棒/Nyoi-bo) is slung diagonally across his back from right shoulder to left waist. Chibi proportions (3-4 head ratio). Hand-drawn outline with slight wobble. 小悟空 must perform the core conceptual action, not decorate the scene. Make 小悟空 energetic, determined, and slightly fierce, not cute or babyish.

Theme:
{正文配图主题}

Structure type:
{结构类型：Workflow / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core idea:
{这张图要表达的核心意思}

Composition:
{具体画面：小悟空在哪里、正在做什么、主要物件是什么、信息如何流动}

Suggested elements:
{元素1} / {元素2} / {元素3} / {元素4}

Chinese handwritten labels:
{标注词1} / {标注词2} / {标注词3} / {标注词4} / {可选标注词5}

Color use:
Character: black spiky hair, white tank top, blue bloomers, red wristbands, red staff. Structural elements: black for main line art and framework. Orange for main flow/path/arrows. Red for key warnings/problems/results. Blue for secondary notes or feedback/system state.

Constraints:
One image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank white space. Use at most 5-8 short handwritten Chinese labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, or dense explainer. Do not copy prior examples or reuse known case compositions unless explicitly requested; invent a fresh visual metaphor for this specific article. It should be clear but not instructional, interesting but not childish, strange but clean. Do not draw Super Saiyan (blonde) Goku — only the black-haired child version. Do not change 小悟空's outfit.
```

## 图像编辑提示

去掉左上角标题：

```text
Edit the provided image. Remove only the handwritten title "{要删除的文字}" and its underline from the top-left corner. Fill that area with the same clean white background, matching the surrounding blank paper. Preserve everything else exactly: characters, labels, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

增强小悟空参与感：

```text
Regenerate this illustration with the same core meaning and simple layout, but make 小悟空 more central to the conceptual action. 小悟空 should be doing the energetic work that explains the idea — swinging his staff, flying, pushing, or fighting — not standing beside the diagram. Keep it clean, sparse, hand-drawn, and not cute.
```
