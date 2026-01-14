
@[TOC](Table of Contents)

---

# Foreword
During the development process with Unreal Engine, we often need to create repetitive functions for projects, or struggle with optimization as projects grow in scale. To improve work efficiency and quickly optimize projects, the Dan--Tools editor tool was developed to meet these needs. With it, you can quickly perform operations on meshes, textures, levels, layers, tags, and other elements.

---

# 1. What is Dan--Tools?

Dan--Tools is an editor tool compatible with **Unreal Engine 5.3** and above versions. This tool integrates frequently used operational functions in daily work.

![Insert image description here](https://i-blog.csdnimg.cn/direct/99c2c6d6d1d84b399beea111953c7d21.png)

# 2. How to Run
## 1. Installation Location
Place the plugin in the Plugins folder under the project directory (create the folder if it does not exist).

![Add image description](https://i-blog.csdnimg.cn/direct/787640bcdda9442d8e22bb1a6656df9f.png)

## 2. Location in the Engine
![请添加图片描述](https://i-blog.csdnimg.cn/direct/055984da11454ad09cde9ce373b5ad38.png)



## 3. Usage in the Engine
Right-click MY_Tools and select "Run Editor Tool Widget".
![请添加图片描述](https://i-blog.csdnimg.cn/direct/37930e4edb92471aa28f689e3b16db97.png)


After clicking, drag the widget to the editor interface to dock it.

![请添加图片描述](https://i-blog.csdnimg.cn/direct/219444763bc54d6983ef3345ead0d0c2.png)

# 3. Interface Display
## 1. Mesh Section
![请添加图片描述](https://i-blog.csdnimg.cn/direct/6adc64fc86d043b7ab59c63c3910fab0.png)


## 2. Material Section
![请添加图片描述](https://i-blog.csdnimg.cn/direct/7e4fa3639c06466285202120b7d44833.png)



## 3. Blueprint Section
![请添加图片描述](https://i-blog.csdnimg.cn/direct/7abb406810444e8097537a1cd4c4e460.png)


## 4. Text Section
![请添加图片描述](https://i-blog.csdnimg.cn/direct/248520cadd994ceca3b76c3b66daca57.png)


## 5. Optimization Section
![请添加图片描述](https://i-blog.csdnimg.cn/direct/be4620bffa9a4be7890497cd694726c1.png)


## 6. Others Section
![请添加图片描述](https://i-blog.csdnimg.cn/direct/cd98009bd5904521b7d9dc9d168ee177.png)
![请添加图片描述](https://i-blog.csdnimg.cn/direct/74044bbe406241ad8cd3749718cb1c5d.png)





# 4. Usage Instructions
## 1. Mesh Section

1. Mobility
Batch select meshes, choose the mobility type, and click ![请添加图片描述](https://i-blog.csdnimg.cn/direct/4fb790030a7247ec8d0a06b618a97e51.png)


2. One-click Ground Snapping
Initial position:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/6b08b5c97f9649f19555e31dcb778759.png)




Position after ground snapping (mesh rotation does not affect ground snapping):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/f3630835e8a94707bfb70efbae23a988.png)



3. Modify Pivot Position (**Note: Center the pivot first before modifying other pivot positions**; modifications will not change the position of other meshes in the scene)
Before modification:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/715a0964adfa42118797de429b0525e4.png)


After modification:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/6152b324b1844125a3c422e81d50cc29.png)



4. Recalculate Normals
Select the mesh and click "Recalculate Normals" to resolve most normal-related issues.

5. Add Subdivision Surface (Increase polygon count and add details)
Before adding:

![请添加图片描述](https://i-blog.csdnimg.cn/direct/cf755ee35a2b428997b8c011df6c2c14.png)


After adding:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/68c4bbde0eaa4a86896e1db65a75d444.png)




6. Set Mesh LOD Group
Before:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/142ef40c343343ac8e4531f60d6f62c8.png)


After:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/c098fca015c84df0bd49628ea9539952.png)



7. Mesh Collision (Takes effect only when the mesh collision complexity is set to "Project Default"; press Alt+C to display collision)

![请添加图片描述](https://i-blog.csdnimg.cn/direct/acb9ae84af9f421aaf6f8687dd076e72.png)



Add Collision:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/76ce7e7477714f448b6f54d67ce04278.png)



Remove Collision:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/d3725cbdd76045eeb4c8f85e779fae9c.png)





8. Random Mesh Rotation

![请添加图片描述](https://i-blog.csdnimg.cn/direct/9b67d0fb9a64482caa845338aeb6407d.png)



9. Cast Shadows
Shadows Enabled:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/5a37982b8ff2454399ac79b5ed057a99.png)


Shadows Disabled:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/073353f9cfb54a199dd657b852ab8fd8.png)




10. Collision Enabled
Initial state (no collision):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/fc51eb3d384e40ad89f5073d3aa6d345.png)


After modification:

![请添加图片描述](https://i-blog.csdnimg.cn/direct/f831928f96b449e8aec067074ae59918.png)



11. Batch Mesh Attachment
First, select a mesh in the scene as the parent object:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/c17d7e93842c473d884c9b143bf571ce.png)



Batch select the meshes to be attached and click "One-click Attach".
![请添加图片描述](https://i-blog.csdnimg.cn/direct/58956b703d8f445ea9b0a92fde487c44.png)




12. One-click Mesh Replacement
First, place the original meshes and replacement meshes into "Old Mesh" and "New Mesh" respectively:

![请添加图片描述](https://i-blog.csdnimg.cn/direct/1273d167206148448bc336b3856f522d.png)




Batch select meshes in the scene (all selected meshes matching the "Old Mesh" will be replaced):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/de667030a62247a0ade9deea1d2c491a.png)




For more features, visit: https://space.bilibili.com/344860590

## 2. Material Section

1. Modify Materials
First, check the mesh's material, add the material to be replaced and the new material, batch select meshes, and click "Modify (Overlay Only)":
![请添加图片描述](https://i-blog.csdnimg.cn/direct/ce36fb424e694ffdae27dbeb7ffb1cd7.png)



After replacement, the material of the source mesh remains unchanged, while the material of the meshes in the scene is updated:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/896e222c95a7499ea085dc2a1169e19b.png)



Source Material Before Modification:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/b176fbb052f54a96875966f9ba05195a.png)






2. One-click Material Generation
Click "One-click Material Generation" without selecting a folder (it will search for all texture paths to generate materials):

![请添加图片描述](https://i-blog.csdnimg.cn/direct/c03e1a5fbe734470834026264d5b56e2.png)


Select a folder containing textures (it will search for textures in the selected location and generate PBR materials):

![请添加图片描述](https://i-blog.csdnimg.cn/direct/38c82d17ffc54710878cc25cafbf8327.png)


Generation Result Display:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/b0176b71ed664882a0847711e552683b.png)



For more features, visit: [https://space.bilibili.com/344860590](https://space.bilibili.com/344860590)

## 3. Blueprint Section
1. Blueprint Generation & Replacement
Select Blueprint Actors:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/3528d3004a3b45c4bc871f584ae8962b.png)



Blueprint Replacement (deletes selected meshes and replaces them with Blueprint Actors):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/2da5ecbba1a94408abb06ceafb56f513.png)


Blueprint Generation (does not delete selected meshes):

![请添加图片描述](https://i-blog.csdnimg.cn/direct/ebe1cdae556e4d64bb1ede80b5af39a2.png)



2. Blueprint Generation & Attachment (generates Blueprint Actors and attaches them to meshes)

![请添加图片描述](https://i-blog.csdnimg.cn/direct/0e850143afe24a74afa4847e4a29d925.png)


For more features, visit: [https://space.bilibili.com/344860590](https://space.bilibili.com/344860590)

## 4. Text Section
1. Batch Tag Operations
Tag Operations (function display):

![请添加图片描述](https://i-blog.csdnimg.cn/direct/0803205a205146a0b50419a4a29f30b6.png)


Before Adding (no tags):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/2c397a841f0b47ae80f9b3565ce4d7a5.png)



Add Tags:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/854aff3f87304d3f80a73410d5b023f8.png)


After Adding:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/318e0386124a4ae6b18e4b99414d9bd4.png)



Replace Tags:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/963317605c2d4c97a0374afc92b193d3.png)


After Replacement:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/49ee3d5d007a46dab46dcf815dc5befb.png)



2. Browser Type Naming
First, select assets in the Content Browser:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/2d559e00e42645d38363ce75e2e1a210.png)


Click "Browser Type Naming" -- After Naming:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/64fa52428e9548b1a480d98df81d65a2.png)



3. Editor Content Naming (select Actors to be renamed)

![请添加图片描述](https://i-blog.csdnimg.cn/direct/ce6ea824b8ac4dc7a0fa9cd00d40b6df.png)


Enter the new name:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/b9511e9a0f964da5944fb413038850fd.png)


Renaming completed with auto-incremented suffix:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/a22d2c6894344033abb28bc651b968ce.png)



For more features, visit: [https://space.bilibili.com/344860590](https://space.bilibili.com/344860590)

## 5. Optimization Section
1. One-click Nanite
First, select meshes in the editor (Nanite is disabled for these assets):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/97ef8700c0bd4dad85b2d03a010bbad1.png)


Select "Enable" and click the button (Nanite is now enabled):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/e8107647a3374de89ab14093f483d146.png)



2. Set Maximum Texture Size (supports batch selection of texture assets)
Before modification: 2048
![请添加图片描述](https://i-blog.csdnimg.cn/direct/1562209794a248b981a1632b34911e93.png)


After modification: 512
![请添加图片描述](https://i-blog.csdnimg.cn/direct/27b2585a50ec4a718d3fa61d14ebc164.png)



3. Texture Offset LOD (Texture MipMaps must be set to "From Texture Group" before using this function)
Before clicking:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/5b4d6c857af544778cae66e57ca24eeb.png)


After clicking:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/d2e4d5fc9a52414995acf5327b1d7119.png)





4. MipMap Toggle
Before toggling:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/cbbc6beac23b4b2aaabd03be8c619ad0.png)


After toggling:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/9527cbc1696e440a8dc896c747ebf0e9.png)



5. One-click Mesh Decimation
First, select meshes to be decimated (current polygon count: 9842):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/bcf3b3accc034771a93ef1512d733786.png)


After clicking "Decimate Mesh" (new polygon count: 4920):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/650c91188ed8453dbc65c5c61caaad80.png)



6. Delete Empty Folders
Currently, folders "111" and "222" in the path are empty:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/14324fef61c04c98b36a2ae590e2f7ca.png)


Click "Delete Folders" (automatically finds empty folders in the project, e.g., "111/222"):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/9dd7e40109ef467388e67d425b4d9181.png)


After confirmation and deletion (folder "222" under "111" is deleted):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/c77866ff4a90470ba4a84f612bab4bd4.png)




7. Delete Unreferenced Assets
First, select assets in the Content Browser and click "Delete Unreferenced":
![请添加图片描述](https://i-blog.csdnimg.cn/direct/53670be8ec3d4ead98d9ee314f71376f.png)


After removing unreferenced assets:
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/d6dc6b3f2b894a7fa53761a10c728f59.png)


Lock Unreferenced Assets (locking assets prevents deletion):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/c5d63ca4d2b4416c8a8a8a1abaf15672.png)



8. Lightmass Importance Volume
Select meshes in the Outliner (currently, Channel 0 is enabled):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/7805e0b382a043ba823df15a866eef90.png)


After clicking "Modify" (Channel 1 is now enabled):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/e0ad82f9c5914a8db31f8d921f0da085.png)



9. One-click Hide
Batch select meshes (currently, "Hidden in Game" is False):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/7fa3430db7004d379ecc04897b637c14.png)

To restore hidden meshes to False (no need to select hidden meshes; select any mesh):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/b0baca38df434891aa37f56359ab07ae.png)


After clicking (meshes are displayed again):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/4998314fe7134516998787c4a4a393d7.png)



10. Fix Texture Compression
Select texture assets in the Content Browser (e.g., the default texture compression is set to "Masks" with SRGB = False, which is incorrect):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/fcb2bbfe90b247bbbafbffeb9c32eccf.png)


Click the "Fix" button (updated to default correct settings):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/c938241bcfea4c558aaa6e1fe2904293.png)



For more features, visit: [https://space.bilibili.com/344860590](https://space.bilibili.com/344860590)

## 6. Others Section
1. Isolate Actor
First, select the Actor to isolate:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/402f4ecaa85a411880450d18f37fbc62.png)




After isolation (press Ctrl+H or Ctrl+Z to show all actors again):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/81a462fc5158410a896d36b82b2190ce.png)

2. One-click Nav Mesh Bounds Volume
First, select meshes to add Nav Mesh Bounds Volume to:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/c1cd527972044533b7ab2270289fd806.png)


After adding (move the NavMeshBoundsVolume to load it properly; green areas are navigation paths, press P to display):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/a92f85a76b37445da4f61b5b5757ac92.png)



3. Change Current Language (supports Chinese/English switching)
    **5.4+ Cancel this function**
Chinese:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/1518ecef887c4f6cad13608632ac46b6.png)


English:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/02c33eea45bc4da68469b9c979479a56.png)



4. Create Folder (in the Content Browser)
First, select the location to create the folder (e.g., inside "1"):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/906c997f68a94f91a28ecf165f3c897e.png)



Click the "Create Folder" button (automatically identifies the selected path and prompts for the folder name; modify the folder name in the relevant function if needed):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/d598e5e59dc24ed3b3801e2d69d296c8.png)


After creation:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/95c135a50dd54c4dba2fadda5994d929.png)



5. Move to Folder
First, select meshes in the Outliner and enter the folder name:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/1e5914a2ebf04a929a8d24a2388154be.png)


After moving:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/200dc9da58834bf2907d362267797543.png)



6. Layer Creation & Import
First, select meshes (no layers currently), enter the layer name:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/fffdfe88207142b7a1b04eedac105de3.png)


After creation and import:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/23733b15fa644f84897d72d045444ba6.png)


Remove Current Layer (select meshes, select the layer name, and click the button):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/6af061afe49c47548e1a2ff1defaf114.png)



7. Generate at Current View Position
First, select the type to generate:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/a4f4f2d8b41346a9b77818153f7fb5f4.png)


After generation (a camera is generated at the current view position):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/0b96a5c6ce874d388d4959ba5b8a6ded.png)



8. One-click Controller Generation (generates a camera view around the selected mesh)
Set the mesh's position as the controller's center point:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/df63de015b2e41f5a095a35153ace319.png)


For testing, set the controller's "Auto Possess Player" to "Player 0":
![请添加图片描述](https://i-blog.csdnimg.cn/direct/9d366d58eae645dc8143b06bebd5c6bc.png)


Run the game to rotate, move, and adjust the camera distance around the mesh:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/a4e3001d942a4d37a4a3b484a816ebf0.png)



9. One-click Time Lock Creation
Enter the time lock date and click "Create" (the game will close automatically at the specified time):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/a62f04d46da74021b689bf5e1d5a7eeb.png)



10. Screenshot Current View
Current view position:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/ab15789c87594df9908fd3d83c37de1b.png)


Click "Screenshot" -- After Screenshot:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/10d3f4d7a3d644d3a999deeadede1bb2.png)



11. Move to Sublevel
Current sublevels (no sublevels):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/426f8a96e99e4502aa25ec4c1487b1ab.png)


Created two sublevels (not displayed at the bottom):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/ab89dc97c3f4475695231b175bf19a8f.png)


Close the editor tool panel and re-run to display sublevels:
![请添加图片描述](https://i-blog.csdnimg.cn/direct/fb3d8a4c0d5d4d5e9d3af1f06bc4f52b.png)


Batch select meshes, select the sublevel, and click "Move to":
![请添加图片描述](https://i-blog.csdnimg.cn/direct/27b72897cc484487b3987aa869d300c0.png)



12. Mesh Data (Length, Width, Height, Volume)
Select the mesh and click "Display Data":
![请添加图片描述](https://i-blog.csdnimg.cn/direct/9c55c2b664cd403ab38d5b241e2e8c66.png)



13. Disable Camera Aspect Ratio Lock
Batch select cameras (current "Aspect Ratio Locked" is True):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/7db12dba8d7c4d3e9abc56718209e817.png)


After clicking (set to False):
![请添加图片描述](https://i-blog.csdnimg.cn/direct/ca1a520299c045a38879caf0fbc53268.png)



For more features, visit: [https://space.bilibili.com/344860590](https://space.bilibili.com/344860590)

# Summary
The above is the usage guide for the Unreal Editor tool Dan--Tools, which is suitable for level design, digital twin, and other projects. It helps improve work efficiency!
