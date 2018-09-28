# <a name="javascript-api-for-office"></a><span data-ttu-id="16041-101">适用于 Office 的 JavaScript API</span><span class="sxs-lookup"><span data-stu-id="16041-101">JavaScript API for Office</span></span>

<span data-ttu-id="16041-102">JavaScript API for Office 使您能够与 Office 主机应用程序中的对象模型创建的 web 应用程序进行交互。</span><span class="sxs-lookup"><span data-stu-id="16041-102">The JavaScript API for Office enables you to create web applications that interact with the object models in Office host applications.</span></span> <span data-ttu-id="16041-103">您的应用程序将引用 office.js 库，它是脚本加载程序。</span><span class="sxs-lookup"><span data-stu-id="16041-103">Your application will reference the office.js library, which is a script loader.</span></span> <span data-ttu-id="16041-104">在 office.js 库加载适用于 Office 应用程序正在运行的加载项对象模型。</span><span class="sxs-lookup"><span data-stu-id="16041-104">The office.js library loads the object models that are applicable to the Office application that is running the add-in.</span></span> <span data-ttu-id="16041-105">您可以使用以下 JavaScript 对象模型：</span><span class="sxs-lookup"><span data-stu-id="16041-105">You can use the following JavaScript object models:</span></span>

- <span data-ttu-id="16041-106">**公共 Api** -引入使用**Office 2013**Api。</span><span class="sxs-lookup"><span data-stu-id="16041-106">**Common APIs** - APIs that were introduced with **Office 2013**.</span></span> <span data-ttu-id="16041-107">这是针对**所有 Office 主机应用程序**加载，与 Office 客户端应用程序连接外接程序应用程序。</span><span class="sxs-lookup"><span data-stu-id="16041-107">This is loaded for **all Office host applications** and connects your add-in application with the Office client application.</span></span> <span data-ttu-id="16041-108">对象模型中包含的特定于 Office 客户端 Api 和适用于多个 Office 客户端主机应用程序的 Api。</span><span class="sxs-lookup"><span data-stu-id="16041-108">The object model contains APIs that are specific to Office clients, and APIs that are applicable to multiple Office client host applications.</span></span> <span data-ttu-id="16041-109">此内容的所有正在**共享的 API**。</span><span class="sxs-lookup"><span data-stu-id="16041-109">All of this content is under **Shared API**.</span></span> 

  <span data-ttu-id="16041-110">**Outlook**也使用的常用语法都 API。</span><span class="sxs-lookup"><span data-stu-id="16041-110">**Outlook** also uses the common API syntax.</span></span> <span data-ttu-id="16041-111">别名 Office 下的所有内容包含可用于编写脚本以便与 Office 文档、 工作表、 演示文稿、 邮件项目和从您 Office 加载项项目中的内容进行交互的对象。如果加载项将面向 Office 2013 和更高版本，则必须使用这些公共 Api。</span><span class="sxs-lookup"><span data-stu-id="16041-111">Everything under the alias Office contains objects you can use to write scripts that interact with content in Office documents, worksheets, presentations, mail items, and projects from your Office Add-ins. You must use these common APIs if your add-in will target Office 2013 and later.</span></span> <span data-ttu-id="16041-112">此对象模型使用回调。</span><span class="sxs-lookup"><span data-stu-id="16041-112">This object model uses callbacks.</span></span>

- <span data-ttu-id="16041-113">**特定于宿主的 Api** -与**Office 2016**引入 Api。</span><span class="sxs-lookup"><span data-stu-id="16041-113">**Host-specific APIs** - APIs that were introduced with **Office 2016**.</span></span> <span data-ttu-id="16041-114">此对象模型提供了特定于宿主的强类型对象对应于时使用 Office 客户端和表示 Office JavaScript Api 的发展，您看到的熟悉对象。</span><span class="sxs-lookup"><span data-stu-id="16041-114">This object model provides host-specific strongly-typed objects that correspond to familiar objects that you see when you use Office clients, and represents the future of Office JavaScript APIs.</span></span> <span data-ttu-id="16041-115">特定于宿主的 Api 当前包括 Word 的 JavaScript API 和 Excel 的 JavaScript API。</span><span class="sxs-lookup"><span data-stu-id="16041-115">The host-specific APIs currently include the Word JavaScript API and the Excel JavaScript API.</span></span>

## <a name="supported-host-applications"></a><span data-ttu-id="16041-116">支持的主机应用程序</span><span class="sxs-lookup"><span data-stu-id="16041-116">Supported host applications</span></span>

- [<span data-ttu-id="16041-117">Excel</span><span class="sxs-lookup"><span data-stu-id="16041-117">Excel</span></span>](overview/excel-add-ins-reference-overview.md)
- [<span data-ttu-id="16041-118">OneNote</span><span class="sxs-lookup"><span data-stu-id="16041-118">OneNote</span></span>](overview/onenote-add-ins-javascript-reference.md)
- [<span data-ttu-id="16041-119">Outlook</span><span class="sxs-lookup"><span data-stu-id="16041-119">Outlook</span></span>](requirement-sets/outlook-api-requirement-sets.md)
- [<span data-ttu-id="16041-120">Visio</span><span class="sxs-lookup"><span data-stu-id="16041-120">Visio</span></span>](overview/visio-javascript-reference-overview.md)
- [<span data-ttu-id="16041-121">Word</span><span class="sxs-lookup"><span data-stu-id="16041-121">Word</span></span>](overview/word-add-ins-reference-overview.md)
- [<span data-ttu-id="16041-122">共享 API</span><span class="sxs-lookup"><span data-stu-id="16041-122">Shared API</span></span>](requirement-sets/office-add-in-requirement-sets.md)

> [!NOTE] 
> <span data-ttu-id="16041-123">[PowerPoint 和 Project](requirement-sets/powerpoint-and-project-note.md)支持使用 JavaScript API 所做的加载项。</span><span class="sxs-lookup"><span data-stu-id="16041-123">[PowerPoint and Project](requirement-sets/powerpoint-and-project-note.md) support add-ins made with the JavaScript API.</span></span> <span data-ttu-id="16041-124">但是，他们当前不具有特定主机的 Api。</span><span class="sxs-lookup"><span data-stu-id="16041-124">However, they currently do not have host-specific APIs.</span></span> <span data-ttu-id="16041-125">您与这些主机通过共享 API 进行交互。</span><span class="sxs-lookup"><span data-stu-id="16041-125">You interact with these hosts through the Shared API.</span></span>

<span data-ttu-id="16041-126">了解有关[支持的主机和其他要求](https://docs.microsoft.com/office/dev/add-ins/concepts/requirements-for-running-office-add-ins)的详细信息。</span><span class="sxs-lookup"><span data-stu-id="16041-126">Learn more about [supported hosts and other requirements](https://docs.microsoft.com/office/dev/add-ins/concepts/requirements-for-running-office-add-ins).</span></span>

## <a name="open-api-specifications"></a><span data-ttu-id="16041-127">开放 API 规范</span><span class="sxs-lookup"><span data-stu-id="16041-127">Open API specifications</span></span>

<span data-ttu-id="16041-p106">在我们设计和开发新的 API 以用于 Office 外接程序时，我们将使它们适用于[开放 API 规范](openspec.md)页的反馈。了解管道中的新增功能，并提供您对我们的设计规范的宝贵意见。</span><span class="sxs-lookup"><span data-stu-id="16041-p106">As we design and develop new APIs for Office Add-ins, we'll make them available for your feedback on our [Open API specifications](openspec.md) page. Find out what new features are in the pipeline, and provide your input on our design specifications.</span></span>

## <a name="see-also"></a><span data-ttu-id="16041-130">另请参阅</span><span class="sxs-lookup"><span data-stu-id="16041-130">See also</span></span>

- [<span data-ttu-id="16041-131">Office 的 JavaScript API 参考 （英文）</span><span class="sxs-lookup"><span data-stu-id="16041-131">Office JavaScript API reference</span></span>](https://docs.microsoft.com/javascript/api/overview/office?view=office-js)