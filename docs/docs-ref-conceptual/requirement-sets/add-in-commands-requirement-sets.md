# <a name="add-in-commands-requirement-sets"></a><span data-ttu-id="dc333-101">加载项命令要求集</span><span class="sxs-lookup"><span data-stu-id="dc333-101">Add-in commands requirement sets</span></span>

<span data-ttu-id="dc333-102">要求集是指各组已命名的 API 成员。</span><span class="sxs-lookup"><span data-stu-id="dc333-102">Requirement sets are named groups of API members.</span></span> <span data-ttu-id="dc333-103">Office 加载项使用清单中指定要求集，或使用运行时检查以确定是否的 Office 主机支持外接程序需要的 Api。</span><span class="sxs-lookup"><span data-stu-id="dc333-103">Office Add-ins use requirement sets specified in the manifest or use a runtime check to determine whether an Office host supports APIs that an add-in needs.</span></span> <span data-ttu-id="dc333-104">有关详细信息，请参阅[Office 版本和要求集](https://docs.microsoft.com/office/dev/add-ins/develop/office-versions-and-requirement-sets)。</span><span class="sxs-lookup"><span data-stu-id="dc333-104">For more information, see [Office versions and requirement sets](https://docs.microsoft.com/office/dev/add-ins/develop/office-versions-and-requirement-sets).</span></span>

<span data-ttu-id="dc333-p102">外接程序命令是 UI 元素，可扩展 Office UI，并在外接程序中启动操作。可以使用加载项命令在功能区上添加按钮，也可以向上下文菜单添加项。有关详细信息，请参阅 [Excel、Word 和 PowerPoint 的加载项命令](https://docs.microsoft.com/office/dev/add-ins/design/add-in-commands)和 [Outlook 的加载项命令](https://docs.microsoft.com/outlook/add-ins/add-in-commands-for-outlook)。</span><span class="sxs-lookup"><span data-stu-id="dc333-p102">Add-in commands are UI elements that extend the Office UI and start actions in your add-in. You can use add-in commands to add a button on the ribbon or an item to a context menu. For more information, see [Add-in commands for Excel, Word, and PowerPoint](https://docs.microsoft.com/office/dev/add-ins/design/add-in-commands) and [Add-in commands for Outlook](https://docs.microsoft.com/outlook/add-ins/add-in-commands-for-outlook).</span></span>

<span data-ttu-id="dc333-p103">外接程序命令的初始版本没有相应的要求集（即，没有 AddinCommands 1.0 要求集）。下表列出了支持初始版本的 Office 主机应用程序，以及这些应用程序的内部版本或版本号。</span><span class="sxs-lookup"><span data-stu-id="dc333-p103">The initial release of add-in commands doesn't have a corresponding requirement set (that is, there isn't an AddinCommands 1.0 requirement set). The following table lists the Office host applications that support the initial release version, and the build versions or number for those applications.</span></span>  

| <span data-ttu-id="dc333-110">发布</span><span class="sxs-lookup"><span data-stu-id="dc333-110">Release</span></span>   |  <span data-ttu-id="dc333-111">Office 2013 for Windows</span><span class="sxs-lookup"><span data-stu-id="dc333-111">Office 2013 for Windows</span></span> | <span data-ttu-id="dc333-112">Office 2016 windows （非订阅）</span><span class="sxs-lookup"><span data-stu-id="dc333-112">Office 2016 for Windows (non-subscription)</span></span> | <span data-ttu-id="dc333-113">用于 Windows 的 office 365</span><span class="sxs-lookup"><span data-stu-id="dc333-113">Office 365 for Windows</span></span>   |  <span data-ttu-id="dc333-114">Office 365 for iPad</span><span class="sxs-lookup"><span data-stu-id="dc333-114">Office 365 for iPad</span></span>  |  <span data-ttu-id="dc333-115">Office 365 for Mac</span><span class="sxs-lookup"><span data-stu-id="dc333-115">Office 365 for Mac</span></span>  | <span data-ttu-id="dc333-116">Office Online</span><span class="sxs-lookup"><span data-stu-id="dc333-116">Office Online</span></span>  |  
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
| <span data-ttu-id="dc333-117">外接程序命令（初始版本，无要求集）</span><span class="sxs-lookup"><span data-stu-id="dc333-117">Add-in commands (initial release, no requirement set)</span></span> | <span data-ttu-id="dc333-118">不适用</span><span class="sxs-lookup"><span data-stu-id="dc333-118">N/A</span></span> | <span data-ttu-id="dc333-119">16.0.4678.1000*在仅限 Outlook 中受支持*</span><span class="sxs-lookup"><span data-stu-id="dc333-119">16.0.4678.1000 *Supported in Outlook only*</span></span> |<span data-ttu-id="dc333-120">版本 1603（内部版本 6769.0000）或更高版本</span><span class="sxs-lookup"><span data-stu-id="dc333-120">Version 1603 (Build 6769.0000) or later</span></span> | <span data-ttu-id="dc333-121">不适用</span><span class="sxs-lookup"><span data-stu-id="dc333-121">N/A</span></span> | <span data-ttu-id="dc333-122">15.33 或更高版本</span><span class="sxs-lookup"><span data-stu-id="dc333-122">15.33 or later</span></span>| <span data-ttu-id="dc333-123">2016 年 1 月</span><span class="sxs-lookup"><span data-stu-id="dc333-123">January 2016</span></span> | |

<span data-ttu-id="dc333-124">外接程序命令 1.1 要求集介绍了[随文档自动打开任务窗格](https://docs.microsoft.com/office/dev/add-ins/develop/automatically-open-a-task-pane-with-a-document)的功能。</span><span class="sxs-lookup"><span data-stu-id="dc333-124">The add-in commands 1.1 requirement set introduces the ability to [autoopen a task pane with documents](https://docs.microsoft.com/office/dev/add-ins/develop/automatically-open-a-task-pane-with-a-document).</span></span>

<span data-ttu-id="dc333-125">下表列出了外接程序命令 1.1 要求集、支持该要求集的 Office 主机应用程序，以及 Office 应用程序的内部版本或版本号。</span><span class="sxs-lookup"><span data-stu-id="dc333-125">The following table lists the add-in commands 1.1 requirement set, the Office host applications that support that requirement set, and the build or version numbers for the Office application.</span></span> 

|  <span data-ttu-id="dc333-126">要求集</span><span class="sxs-lookup"><span data-stu-id="dc333-126">Requirement set</span></span>  |  <span data-ttu-id="dc333-127">Office 2013 for Windows</span><span class="sxs-lookup"><span data-stu-id="dc333-127">Office 2013 for Windows</span></span> | <span data-ttu-id="dc333-128">Office 2016 windows （非订阅）</span><span class="sxs-lookup"><span data-stu-id="dc333-128">Office 2016 for Windows (non-subscription)</span></span> | <span data-ttu-id="dc333-129">用于 Windows 的 office 365</span><span class="sxs-lookup"><span data-stu-id="dc333-129">Office 365 for Windows</span></span>   |  <span data-ttu-id="dc333-130">Office 365 for iPad</span><span class="sxs-lookup"><span data-stu-id="dc333-130">Office 365 for iPad</span></span>  |  <span data-ttu-id="dc333-131">Office 365 for Mac</span><span class="sxs-lookup"><span data-stu-id="dc333-131">Office 365 for Mac</span></span>  | <span data-ttu-id="dc333-132">Office Online</span><span class="sxs-lookup"><span data-stu-id="dc333-132">Office Online</span></span>  |  
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
| <span data-ttu-id="dc333-133">AddinCommands 1.1</span><span class="sxs-lookup"><span data-stu-id="dc333-133">AddinCommands 1.1</span></span>  | <span data-ttu-id="dc333-134">不适用</span><span class="sxs-lookup"><span data-stu-id="dc333-134">N/A</span></span> | <span data-ttu-id="dc333-135">16.0.4678.1000*在仅限 Outlook 中受支持*</span><span class="sxs-lookup"><span data-stu-id="dc333-135">16.0.4678.1000 *Supported in Outlook only*</span></span>  | <span data-ttu-id="dc333-136">版本 1705（内部版本 8121.1000）或更高版本</span><span class="sxs-lookup"><span data-stu-id="dc333-136">Version 1705 (Build 8121.1000) or later</span></span> | <span data-ttu-id="dc333-137">不适用</span><span class="sxs-lookup"><span data-stu-id="dc333-137">N/A</span></span> | <span data-ttu-id="dc333-138">15.34 或更高版本</span><span class="sxs-lookup"><span data-stu-id="dc333-138">15.34 or later</span></span>| <span data-ttu-id="dc333-139">2017 年 5 月</span><span class="sxs-lookup"><span data-stu-id="dc333-139">May 2017</span></span> | |

<span data-ttu-id="dc333-140">若要详细了解版本、内部版本号和 Office Online Server，请参阅：</span><span class="sxs-lookup"><span data-stu-id="dc333-140">To find out more about versions, build numbers, and Office Online Server, see:</span></span>

- [<span data-ttu-id="dc333-141">更新频道发布的 Office 365 客户端版本号和内部版本号</span><span class="sxs-lookup"><span data-stu-id="dc333-141">Version and build numbers of update channel releases for Office 365 clients</span></span>](https://support.office.com/article/version-and-build-numbers-of-update-channel-releases-ae942449-1fca-4484-898b-a933ea23def7)
- [<span data-ttu-id="dc333-142">使用的是哪一版 Office？</span><span class="sxs-lookup"><span data-stu-id="dc333-142">What version of Office am I using?</span></span>](https://support.office.com/article/What-version-of-Office-am-I-using-932788b8-a3ce-44bf-bb09-e334518b8b19)
- [<span data-ttu-id="dc333-143">在哪里可以找到 Office 365 客户端应用程序的版本号和内部版本号</span><span class="sxs-lookup"><span data-stu-id="dc333-143">Where you can find the version and build number for an Office 365 client application</span></span>](https://support.office.com/article/version-and-build-numbers-of-update-channel-releases-ae942449-1fca-4484-898b-a933ea23def7)
- <span data-ttu-id="dc333-144">
  [Office Online Server 概述](https://docs.microsoft.com/officeonlineserver/office-online-server-overview)</span><span class="sxs-lookup"><span data-stu-id="dc333-144">[Office Online Server overview](https://docs.microsoft.com/officeonlineserver/office-online-server-overview)</span></span>

## <a name="office-common-api-requirement-sets"></a><span data-ttu-id="dc333-145">Office 通用 API 要求集</span><span class="sxs-lookup"><span data-stu-id="dc333-145">Office common API requirement sets</span></span>

<span data-ttu-id="dc333-146">有关公用 API 要求集的信息，请参阅 [Office 公用 API 要求集](office-add-in-requirement-sets.md)。</span><span class="sxs-lookup"><span data-stu-id="dc333-146">For information about common API requirement sets, see [Office common API requirement sets](office-add-in-requirement-sets.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="dc333-147">另请参阅</span><span class="sxs-lookup"><span data-stu-id="dc333-147">See also</span></span>

- [<span data-ttu-id="dc333-148">Office 版本和要求集</span><span class="sxs-lookup"><span data-stu-id="dc333-148">Office versions and requirement sets</span></span>](https://docs.microsoft.com/office/dev/add-ins/develop/office-versions-and-requirement-sets)
- [<span data-ttu-id="dc333-149">指定 Office 主机和 API 要求</span><span class="sxs-lookup"><span data-stu-id="dc333-149">Specify Office hosts and API requirements</span></span>](https://docs.microsoft.com/office/dev/add-ins/develop/specify-office-hosts-and-api-requirements)
- [<span data-ttu-id="dc333-150">Office 外接程序 XML 清单</span><span class="sxs-lookup"><span data-stu-id="dc333-150">Office Add-ins XML manifest</span></span>](https://docs.microsoft.com/office/dev/add-ins/develop/add-in-manifests)