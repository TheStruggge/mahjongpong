# 首页图片资源

首页默认首先显示，点击开始恢复当前关卡。仅右上角设置按钮，无任务栏或成就按钮。

可直接替换同名 PNG：
- `background.png`：全屏森林遗迹背景，使用 object-fit: cover 自适应铺满。
- `logo.png`：临时麻将对对消 Logo，透明 PNG，保留透明通道。
- `button-start.png`：金边绿色按钮底图，透明 PNG；“开始”和当前关卡号由组件动态绘制，不要烘焙进图片。

生成方式：内置 image_gen 工具。参考图仅用于背景的风格和构图。素材复制到本目录，运行时不依赖生成工具目录。

## 最终生成提示词

### Background

Use case: stylized-concept. Generate ONE production-ready PNG background only for a portrait mobile mahjong game home screen, 1024x2048 or similar tall 1:2 aspect ratio. Reference image is a style and composition reference only. Depict lush overgrown ancient stone ruins: tall mossy columns framing both sides, a great arch high in center, ivy cascading from upper corners, warm pale golden sunlight entering the central clearing, worn steps and a quiet shallow reflecting pool around middle, scattered small white flowers and grasses in the lower foreground. Painterly storybook game environment, visible brush texture, soft layered green and jade foliage, luminous yellow-green sunlit highlights, peaceful inviting atmosphere. Composition similar to reference, bright center with gentle visual space at upper quarter for separate logo and lower quarter for separate start button. Fill the entire canvas edge to edge. NO lettering, NO logo, NO buttons, NO UI, NO badges, NO task board, NO characters, NO watermark. Only the landscape illustration.

### Logo

Use case: logo-brand. Generate one transparent-background PNG logo asset for a cheerful mahjong matching mobile game. Exact Chinese title text: "麻将对对消" arranged on two compact centered lines, first line "麻将", second line "对对消". Big rounded playful golden-yellow 3D lettering with cream highlights, orange bevel, thick warm dark-brown carved wood extrusion/shadow. One small ivory mahjong tile with a green bamboo symbol tucked behind upper left of lettering. Friendly polished casual puzzle-game aesthetic. No scenery, no panel, no buttons, no other words, no watermark. Genuine transparent alpha background, logo fills canvas with modest 5% clear margin, approximately 3:2 aspect ratio. Legible text and clean cutout silhouette. This is a temporary replaceable game logo.

### Start button

Use case: ui-mockup. Create ONE isolated mobile casual-game start-button image asset, PNG with genuinely transparent background. Wide horizontal rounded rectangular button, width-to-height approximately 2.85:1, close fit within canvas with just 3% transparent padding for shadow. Thick polished golden-yellow rim, warm orange bevel and dimensional lower edge, emerald green dark inner edge, vibrant lime green glossy main face smoothly grading to rich leaf green at the bottom, small soft white reflected highlight near the upper left of green face. Friendly chunky 3D puzzle game aesthetic, straight-on orthographic front view, symmetric button, subtle dark-brown drop shadow beneath. Center face completely empty for dynamic text to be overlaid in HTML. NO text, NO symbols, NO icons, NO letters, NO scenery, NO background panel, NO watermark.

