# <a name="onenote-javascript-api-requirement-sets"></a><span data-ttu-id="2fe46-101">OneNote JavaScript API 要求集</span><span class="sxs-lookup"><span data-stu-id="2fe46-101">OneNote JavaScript API requirement sets</span></span>

<span data-ttu-id="2fe46-102">要求集是指各组已命名的 API 成员。</span><span class="sxs-lookup"><span data-stu-id="2fe46-102">Requirement sets are named groups of API members.</span></span> <span data-ttu-id="2fe46-103">Office 加载项使用清单中指定要求集，或使用运行时检查以确定是否的 Office 主机支持外接程序需要的 Api。</span><span class="sxs-lookup"><span data-stu-id="2fe46-103">Office Add-ins use requirement sets specified in the manifest or use a runtime check to determine whether an Office host supports APIs that an add-in needs.</span></span> <span data-ttu-id="2fe46-104">有关详细信息，请参阅[Office 版本和要求集](https://docs.microsoft.com/office/dev/add-ins/develop/office-versions-and-requirement-sets)。</span><span class="sxs-lookup"><span data-stu-id="2fe46-104">For more information, see [Office versions and requirement sets](https://docs.microsoft.com/office/dev/add-ins/develop/office-versions-and-requirement-sets).</span></span>

<span data-ttu-id="2fe46-105">下表列出了 OneNote 要求集、支持这些要求集的 Office 主机应用程序，以及这些应用程序的内部版本或发布日期。</span><span class="sxs-lookup"><span data-stu-id="2fe46-105">The following table lists the OneNote requirement sets, the Office host applications that support those requirement sets, and the build versions or availability date.</span></span>

|  <span data-ttu-id="2fe46-106">要求集</span><span class="sxs-lookup"><span data-stu-id="2fe46-106">Requirement set</span></span>  |  <span data-ttu-id="2fe46-107">Office Online</span><span class="sxs-lookup"><span data-stu-id="2fe46-107">Office Online</span></span> | 
|:-----|:-----|
| <span data-ttu-id="2fe46-108">OneNoteApi 1.1</span><span class="sxs-lookup"><span data-stu-id="2fe46-108">OneNoteApi 1.1</span></span>  | <span data-ttu-id="2fe46-109">2016 年 9 月</span><span class="sxs-lookup"><span data-stu-id="2fe46-109">September 2016</span></span> |  

## <a name="office-common-api-requirement-sets"></a><span data-ttu-id="2fe46-110">Office 通用 API 要求集</span><span class="sxs-lookup"><span data-stu-id="2fe46-110">Office common API requirement sets</span></span>

<span data-ttu-id="2fe46-111">若要了解通用 API 要求集，请参阅 [Office 通用 API 要求集](office-add-in-requirement-sets.md)。</span><span class="sxs-lookup"><span data-stu-id="2fe46-111">For information about common API requirement sets, see [Office common API requirement sets](office-add-in-requirement-sets.md).</span></span>

## <a name="onenote-javascript-api-11"></a><span data-ttu-id="2fe46-112">OneNote JavaScript API 1.1</span><span class="sxs-lookup"><span data-stu-id="2fe46-112">OneNote JavaScript API 1.1</span></span> 

<span data-ttu-id="2fe46-113">OneNote JavaScript API 1.1 是首版 API。</span><span class="sxs-lookup"><span data-stu-id="2fe46-113">OneNote JavaScript API 1.1 is the first version of the API.</span></span> <span data-ttu-id="2fe46-114">有关 API 的详细信息，请参阅[OneNote JavaScript API 编程概述 （英文）](https://docs.microsoft.com/office/dev/add-ins/onenote/onenote-add-ins-programming-overview)。</span><span class="sxs-lookup"><span data-stu-id="2fe46-114">For details about the API, see the [OneNote JavaScript API programming overview](https://docs.microsoft.com/office/dev/add-ins/onenote/onenote-add-ins-programming-overview).</span></span>

## <a name="runtime-requirement-support-check"></a><span data-ttu-id="2fe46-115">运行时要求支持检查</span><span class="sxs-lookup"><span data-stu-id="2fe46-115">Runtime requirement support check</span></span>

<span data-ttu-id="2fe46-116">在运行时期间，加载项可以执行下列检查，确定特定主机是否支持 API 要求集：</span><span class="sxs-lookup"><span data-stu-id="2fe46-116">During the runtime, add-ins can check if a particular host supports an API requirement set by doing the following-check:</span></span> 

```js
if (Office.context.requirements.isSetSupported('OneNoteApi', 1.1) === true) {
  /// perform actions
}
else {
  /// provide alternate flow/logic
}
```

## <a name="manifest-based-requirement-support-check"></a><span data-ttu-id="2fe46-117">基于清单的要求支持检查</span><span class="sxs-lookup"><span data-stu-id="2fe46-117">Manifest-based requirement support check</span></span>

<span data-ttu-id="2fe46-p103">只能使用外接程序清单中的 Requirements 元素指定外接程序必须使用的关键要求集或 API 成员。如果 Office 主机或平台不支持在 Requirements 元素中指定的要求集或 API 成员，则外接程序将无法在该主机或平台上运行，并且不会显示在“我的外接程序”中。</span><span class="sxs-lookup"><span data-stu-id="2fe46-p103">Use the Requirements element in the add-in manifest to specify critical requirement sets or API members that your add-in must use. If the Office host or platform doesn't support the requirement sets or API members specified in the Requirements element, the add-in won't run in that host or platform, and won't display in My Add-ins.</span></span>

<span data-ttu-id="2fe46-120">下面的代码示例展示了加载所有 支持第 1.1 版 OneNoteApi 要求集的 Office 主机应用程序的加载项。</span><span class="sxs-lookup"><span data-stu-id="2fe46-120">The following code example shows an add-in that loads in all Office host applications that support the OneNoteApi requirement set, version 1.1.</span></span>

```xml
<Requirements>
   <Sets DefaultMinVersion="1.1">
      <Set Name="OneNoteApi" MinVersion="1.1"/>
   </Sets>
</Requirements>
```

## <a name="see-also"></a><span data-ttu-id="2fe46-121">另请参阅</span><span class="sxs-lookup"><span data-stu-id="2fe46-121">See also</span></span>

- [<span data-ttu-id="2fe46-122">Office 版本和要求集</span><span class="sxs-lookup"><span data-stu-id="2fe46-122">Office versions and requirement sets</span></span>](https://docs.microsoft.com/office/dev/add-ins/develop/office-versions-and-requirement-sets)
- [<span data-ttu-id="2fe46-123">指定 Office 主机和 API 要求</span><span class="sxs-lookup"><span data-stu-id="2fe46-123">Specify Office hosts and API requirements</span></span>](https://docs.microsoft.com/office/dev/add-ins/develop/specify-office-hosts-and-api-requirements)
- [<span data-ttu-id="2fe46-124">Office 外接程序 XML 清单</span><span class="sxs-lookup"><span data-stu-id="2fe46-124">Office Add-ins XML manifest</span></span>](https://docs.microsoft.com/office/dev/add-ins/develop/add-in-manifests)