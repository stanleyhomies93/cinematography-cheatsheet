# Cinematography AI Video Prompt Cheat Sheet
**10 categories · 31 parameters · 199 total values**
Built for: Seedance / Kling / Runway / Sora

---

## 1. ◎ Lens & Optics (4 params · 26 values)
*Controls how the image is optically rendered — sharpness, compression, bokeh shape, flare character*

### Focal Length (10)
| Value | Effect |
|---|---|
| `14mm` | Ultra-wide, extreme distortion, dramatic interiors |
| `18mm` | Wide, environmental, slight barrel distortion |
| `24mm` | Wide standard, documentary, landscapes |
| `28mm` | Street photography classic, Kubrick favorite |
| `35mm` | Natural perspective, closest to human eye |
| `50mm` | Normal lens, clean neutral look |
| `58mm` | Portrait-adjacent, dreamy rendering (Noctilux) |
| `85mm` | Portrait telephoto, flattering compression |
| `100mm` | Tight portrait, strong background compression |
| `135mm+` | Extreme compression, voyeuristic feel, paparazzi |

### Lens Type (6)
| Value | Effect |
|---|---|
| `anamorphic` | Oval bokeh, horizontal flare, widescreen look |
| `spherical` | Standard round bokeh, neutral rendering |
| `vintage / uncoated` | Lower contrast, warm flares, organic |
| `tilt-shift` | Selective focus plane, miniature effect |
| `macro` | Extreme close-up capability, razor-thin DOF |
| `fisheye` | 180° barrel distortion, skate/music video |

### Depth of Field (5)
| Value | Effect |
|---|---|
| `shallow DOF` | f/1.2–2.8, subject isolated, creamy blur |
| `moderate DOF` | f/4–5.6, subject sharp with soft context |
| `deep DOF` | f/8–11, most of scene sharp |
| `infinite DOF` | f/16+, everything tack sharp, landscape |
| `split diopter` | Two focal planes sharp simultaneously, De Palma |

### Bokeh & Flare (5)
| Value | Effect |
|---|---|
| `oval bokeh` | Anamorphic signature, elliptical highlights |
| `circular bokeh` | Spherical lens, round specular highlights |
| `cat-eye bokeh` | Swirly edge distortion, vintage lenses |
| `horizontal lens flare` | Anamorphic streak across frame |
| `starburst flare` | Stopped-down aperture, pointed rays |

---

## 2. ▭ Aspect Ratio & Format (2 params · 12 values)
*Frame shape — directly triggers genre associations in AI models*

### Aspect Ratio (7)
| Value | Effect |
|---|---|
| `1:1` | Square, Instagram, symmetric compositions |
| `4:3` | Classic TV/Academy, Wes Anderson, A24 dramas |
| `16:9` | Modern HD standard, TV, YouTube |
| `1.85:1` | US theatrical widescreen, comedies, dramas |
| `2.00:1` | Univisium, Netflix originals, modern compromise |
| `2.39:1` | CinemaScope, blockbusters, spy/action films |
| `2.76:1` | Ultra Panavision, epic scale (Hateful Eight) |

### Film Stock / Sensor (5)
| Value | Effect |
|---|---|
| `35mm film` | Classic cinema grain, natural color |
| `16mm film` | Heavy grain, indie/documentary feel |
| `8mm film` | Home movie, lo-fi, nostalgic |
| `digital clean` | Modern, sharp, clinical (RED/ARRI) |
| `IMAX 65mm` | Massive resolution, Nolan-scale clarity |

---

## 3. ⟁ Camera Angle & Height (3 params · 16 values)
*Where the camera sits relative to the subject — controls power dynamics and psychology*

### Vertical Angle (7)
| Value | Effect |
|---|---|
| `worm's eye` | Ground level looking straight up, extreme power |
| `low angle` | Below eye level, subject dominant/threatening |
| `slightly low angle` | Subtle hero framing, flattering |
| `eye level` | Neutral, documentary, equal relationship |
| `slightly high angle` | Subject slightly vulnerable/smaller |
| `high angle` | Subject diminished, powerless, exposed |
| `bird's eye / top-down` | God view, omniscient, graphic compositions |

### Horizontal Angle (6)
| Value | Effect |
|---|---|
| `frontal` | Direct address, confrontational, Kubrick |
| `three-quarter` | Most common portrait angle, natural |
| `profile / side` | 90° side view, graphic, editorial |
| `three-quarter rear` | Mystery, partial concealment |
| `rear / behind` | Following, voyeuristic, journey |
| `over-the-shoulder` | POV-adjacent, dialogue standard |

### Dutch / Tilt (3)
| Value | Effect |
|---|---|
| `level horizon` | Stable, neutral, standard |
| `slight dutch angle` | Subtle unease, tension |
| `extreme dutch angle` | Disorientation, horror, chaos |

---

## 4. ⊞ Shot Size & Framing (2 params · 15 values)
*How much of the subject and environment is visible in frame*

### Shot Size (10)
| Value | Effect |
|---|---|
| `extreme wide / establishing` | Tiny subject in vast environment, location |
| `wide / full shot` | Full body + surrounding environment |
| `medium wide / cowboy` | Knees up, western framing |
| `medium shot` | Waist up, conversational standard |
| `medium close-up` | Chest up, emotional but contextual |
| `close-up` | Face fills frame, intimate, emotional |
| `extreme close-up` | Eyes only, macro detail, intensity |
| `insert shot` | Object/hand detail, narrative emphasis |
| `two-shot` | Two subjects in frame together |
| `over-the-shoulder (OTS)` | Foreground shoulder/head, background subject |

### Framing Placement (5)
| Value | Effect |
|---|---|
| `centered framing` | Subject dead center, Kubrick/Anderson |
| `rule of thirds` | Subject offset at third intersections |
| `negative space` | Subject small in large empty area |
| `tight / no headroom` | Claustrophobic, uncomfortable |
| `frame within frame` | Doorway, window, arch framing subject |

---

## 5. ⟿ Camera Movement (3 params · 19 values)
*How the camera physically moves through space during the shot*

### Stabilization Type (6)
| Value | Effect |
|---|---|
| `locked off / tripod` | Static, stable, controlled |
| `handheld` | Organic shake, urgency, documentary |
| `steadicam` | Smooth floating glide, Kubrick hallways |
| `gimbal stabilized` | Modern ultra-smooth, YouTube/commercial |
| `dolly` | Tracked smooth movement, precise |
| `crane / jib` | Vertical sweep, reveals, epic scale |

### Movement Direction (9)
| Value | Effect |
|---|---|
| `push in / dolly in` | Moving toward subject, increasing intimacy |
| `pull out / dolly out` | Moving away, revealing context |
| `tracking left/right` | Lateral following movement |
| `tracking backward` | Subject walks toward camera, hero walk |
| `boom up / crane up` | Rising vertical, reveal or triumph |
| `boom down` | Descending, settling, arrival |
| `orbit / arc` | Circling around subject, dramatic |
| `whip pan` | Fast horizontal blur transition |
| `vertigo / dolly zoom` | Zoom in + dolly out simultaneously, dread |

### Speed (4)
| Value | Effect |
|---|---|
| `slow creep` | Barely perceptible movement, tension building |
| `steady pace` | Matching subject walk speed |
| `accelerating` | Building urgency through speed increase |
| `crash zoom / snap` | Sudden violent movement, shock |

---

## 6. ◐ Lighting (4 params · 23 values)
*Light quality, direction, and mood — the single biggest factor in visual tone*

### Key Light Quality (5)
| Value | Effect |
|---|---|
| `hard light` | Sharp shadows, high contrast, dramatic |
| `soft light` | Diffused, gentle gradients, flattering |
| `overcast daylight` | Nature's softbox, even flat light |
| `dappled light` | Broken through trees/blinds, textured |
| `practical lights only` | In-scene lamps, realistic, moody |

### Light Direction (7)
| Value | Effect |
|---|---|
| `front lit` | Flat, even, commercial/beauty |
| `side lit / Rembrandt` | Triangle on cheek, classic portrait |
| `edge / rim light` | Backlight outlining subject, separation |
| `backlit / silhouette` | Subject dark against bright background |
| `top light` | Overhead, Godfather eyes-in-shadow |
| `under light` | Horror, unnatural, campfire |
| `halo / hair light` | Glow around head/hair, angelic |

### Exposure & Key (5)
| Value | Effect |
|---|---|
| `high-key` | Bright, minimal shadows, comedy/commercial |
| `low-key` | Mostly dark, dramatic pools of light, noir |
| `blown-out / overexposed` | Ethereal, dreamy, heavenly |
| `crushed blacks` | Deep shadows with no detail, stylized |
| `natural exposure` | Balanced, realistic, documentary |

### Time of Day / Source (6)
| Value | Effect |
|---|---|
| `golden hour` | Warm low sun, long shadows, magic |
| `blue hour` | Pre-dawn/post-sunset, cool ambient |
| `harsh midday sun` | Overhead, hard shadows, hot |
| `moonlight / night` | Cool blue, low light, mysterious |
| `neon / artificial` | Urban night, colored, cyberpunk |
| `candlelight / firelight` | Warm flicker, intimate, period |

---

## 7. ◧ Color & Grading (3 params · 19 values)
*Post-production color manipulation — the 'Instagram filter' of cinema but far more precise*

### Color Temperature (5)
| Value | Effect |
|---|---|
| `warm / amber` | Cozy, nostalgic, golden, Spielberg |
| `cool / blue` | Clinical, cold, isolated, thriller |
| `neutral` | Balanced white, documentary, natural |
| `mixed warm-cool` | Warm practicals against cool ambient |
| `extreme tungsten` | Very orange, sodium vapor, gritty |

### Color Palette / Grade (10)
| Value | Effect |
|---|---|
| `teal and orange` | Hollywood blockbuster standard, complementary |
| `teal / cyan grade` | Thriller, cold tension, Fincher |
| `desaturated` | Muted, gritty realism, war/drama |
| `monochromatic` | Single hue variations, stylized |
| `black and white` | Timeless, graphic, art house |
| `pastel` | Soft, dreamy, Wes Anderson, whimsical |
| `saturated / vivid` | Heightened reality, fantasy, pop |
| `cross-processed` | Shifted hues, 90s fashion, experimental |
| `bleach bypass` | Desaturated + high contrast, Saving Private Ryan |
| `day for night` | Shot in day, graded blue to simulate night |

### Film Grain / Texture (4)
| Value | Effect |
|---|---|
| `clean / no grain` | Modern digital, smooth, pristine |
| `fine grain` | 35mm subtle texture, cinematic |
| `heavy grain` | 16mm, gritty, raw, indie |
| `halation / glow` | Light bleed on highlights, vintage warmth |

---

## 8. ◫ Composition & Staging (3 params · 14 values)
*How subjects and environment are arranged within the frame — visual storytelling geometry*

### Perspective & Lines (5)
| Value | Effect |
|---|---|
| `single-point perspective` | One vanishing point, Kubrick hallways |
| `two-point perspective` | Corner view, architectural, dynamic |
| `converging leading lines` | Lines pull eye to focal point |
| `diagonal composition` | Dynamic tension, movement, energy |
| `horizontal layering` | Foreground/mid/background stacking, depth |

### Depth Staging (5)
| Value | Effect |
|---|---|
| `foreground element / frame` | Object close to camera creating depth |
| `deep staging` | Action at multiple depth planes |
| `flat staging` | Everything on one plane, graphic, tableaux |
| `rack focus between planes` | Shift attention between depth layers |
| `silhouette foreground` | Dark foreground shape framing lit subject |

### Subject Placement (4)
| Value | Effect |
|---|---|
| `isolated subject` | Character alone, emphasis on solitude |
| `crowd / ensemble staging` | Multiple subjects, social dynamics |
| `symmetrical staging` | Mirror-image balance, formality |
| `triangular composition` | Three-point grouping, classical stability |

---

## 9. ❖ Genre & Aesthetic Reference (3 params · 29 values)
*Shorthand genre labels that trigger whole visual systems in the AI model's understanding*

### Genre Keywords (14)
| Value | Effect |
|---|---|
| `spy thriller` | Cool tones, urban, tension, surveillance |
| `film noir` | B&W, hard shadows, rain, femme fatale |
| `neo-noir` | Color noir, neon, Blade Runner, Refn |
| `horror` | Dark, desaturated, under-lit, dread |
| `sci-fi` | Blue/teal, clean/gritty, futuristic lighting |
| `western` | Warm amber, wide landscapes, dusty |
| `romantic drama` | Warm, soft, golden hour, intimate |
| `war film` | Desaturated, gritty, handheld, chaos |
| `documentary` | Natural light, handheld, raw, unpolished |
| `music video` | Stylized, colored lighting, fast cuts |
| `fashion editorial` | Beauty light, graphic, high contrast |
| `anime / animation` | Saturated, dramatic lighting, stylized |
| `cyberpunk` | Neon, rain, dark, blue-pink-purple |
| `period drama` | Warm, candlelit, painterly, soft |

### Director/DP Aesthetic (10)
| Value | Effect |
|---|---|
| `Kubrick style` | Symmetry, one-point perspective, cold |
| `Spielberg style` | Warm, backlit, lens flare, wonder |
| `Fincher style` | Dark, desaturated teal, precise, clinical |
| `Wes Anderson style` | Centered, pastel, planimetric, whimsical |
| `Christopher Nolan style` | IMAX, practical, grounded, epic scale |
| `Denis Villeneuve style` | Atmospheric, scale, Deakins lighting |
| `Roger Deakins lighting` | Motivated naturalism, sculptural light |
| `Emmanuel Lubezki style` | Long takes, natural light, wide angle |
| `Wong Kar-wai style` | Saturated, step-printed, neon, romantic |
| `Michael Mann style` | Digital night, urban, blue, heat shimmer |

### Era / Movement (5)
| Value | Effect |
|---|---|
| `1970s New Hollywood` | Gritty, natural, handheld, antiestablishment |
| `1980s blockbuster` | Warm, high-key, anamorphic, Spielberg/Lucas |
| `1990s indie` | Lo-fi, 16mm, raw, Sundance aesthetic |
| `2000s digital transition` | Early digital, clean, green-tinted Matrix |
| `modern cinematic` | Hybrid digital, anamorphic, teal-orange |

---

## 10. ⌂ Production Design (4 params · 26 values)
*Physical world elements — wardrobe, props, locations, textures — that ground the image in reality*

### Location Type (10)
| Value | Effect |
|---|---|
| `European city / old town` | Stone, cobblestone, muted architecture |
| `industrial / warehouse` | Metal, concrete, gritty texture |
| `narrow alley` | Compressed depth, converging walls |
| `neon-lit street` | Asian metropolis, reflections, color |
| `interior studio` | Controlled lighting, clean or dressed |
| `rooftop urban` | Skyline backdrop, open, wind |
| `forest / nature` | Organic, dappled light, green |
| `desert / arid` | Warm, harsh, minimalist landscape |
| `underwater` | Blue-green, caustics, floating |
| `futuristic / sci-fi set` | Clean surfaces, LED panels, minimal |

### Wardrobe Cues (6)
| Value | Effect |
|---|---|
| `black leather jacket` | Action, rebel, spy, urban cool |
| `trench coat` | Noir, spy, authority, rain |
| `suit / tailored` | Power, corporate, Bond |
| `casual / streetwear` | Relatable, urban, young |
| `period costume` | Historical, specific era |
| `tactical / military gear` | Action, operator, war |

### Texture & Material (6)
| Value | Effect |
|---|---|
| `stone / concrete wall` | Hard, cold, urban, texture |
| `brick / terracotta` | Warm industrial, contrasts cool grade |
| `glass / reflections` | Modern, layered, mirror, doubles |
| `metal / rust` | Decay, industrial, gritty |
| `wood / organic` | Warm, natural, cabin, rural |
| `wet surfaces / rain` | Reflections, noir, atmosphere |

### Color Props / Accents (4)
| Value | Effect |
|---|---|
| `red accent object` | Blood, danger, passion, draws eye |
| `blue accent object` | Cool, calm, contrast warm scenes |
| `green accent (neon/foliage)` | Nature, Matrix, sickness, alien |
| `yellow / amber accent` | Warmth, caution, sodium vapor |

---

## Quick Copy Template

```
"[lighting], [aspect ratio], [lens type], [DOF], [color grade]
Shot N (Xs-Ys): [shot size], [camera angle], [subject description], [action], [environment], [color grade], [lens], [focal length], [DOF], [genre aesthetic]"
```
