
# <a name="mailbox"></a><span data-ttu-id="b5e1f-101">mailbox</span><span class="sxs-lookup"><span data-stu-id="b5e1f-101">mailbox</span></span>

### <span data-ttu-id="b5e1f-p101">[Office](Office.md)[.context](Office.context.md). mailbox</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p101">[Office](Office.md)[.context](Office.context.md). mailbox</span></span>

<span data-ttu-id="b5e1f-104">Microsoft Outlook 和 Microsoft Outlook on the web 提供对 Outlook 加载项对象模型的访问。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-104">Provides access to the Outlook add-in object model for Microsoft Outlook and Microsoft Outlook on the web.</span></span>

##### <a name="requirements"></a><span data-ttu-id="b5e1f-105">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-105">Requirements</span></span>

|<span data-ttu-id="b5e1f-106">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-106">Requirement</span></span>| <span data-ttu-id="b5e1f-107">值</span><span class="sxs-lookup"><span data-stu-id="b5e1f-107">Value</span></span>|
|---|---|
|[<span data-ttu-id="b5e1f-108">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="b5e1f-108">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="b5e1f-109">1.0</span><span class="sxs-lookup"><span data-stu-id="b5e1f-109">1.0</span></span>|
|[<span data-ttu-id="b5e1f-110">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="b5e1f-110">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="b5e1f-111">受限</span><span class="sxs-lookup"><span data-stu-id="b5e1f-111">Restricted</span></span>|
|[<span data-ttu-id="b5e1f-112">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="b5e1f-112">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="b5e1f-113">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="b5e1f-113">Compose or read</span></span>|

##### <a name="members-and-methods"></a><span data-ttu-id="b5e1f-114">成员和方法</span><span class="sxs-lookup"><span data-stu-id="b5e1f-114">Members and methods</span></span>

| <span data-ttu-id="b5e1f-115">成员</span><span class="sxs-lookup"><span data-stu-id="b5e1f-115">Member</span></span> | <span data-ttu-id="b5e1f-116">类型</span><span class="sxs-lookup"><span data-stu-id="b5e1f-116">Type</span></span> |
|--------|------|
| [<span data-ttu-id="b5e1f-117">ewsUrl</span><span class="sxs-lookup"><span data-stu-id="b5e1f-117">ewsUrl</span></span>](#ewsurl-string) | <span data-ttu-id="b5e1f-118">成员</span><span class="sxs-lookup"><span data-stu-id="b5e1f-118">Member</span></span> |
| [<span data-ttu-id="b5e1f-119">restUrl</span><span class="sxs-lookup"><span data-stu-id="b5e1f-119">restUrl</span></span>](#resturl-string) | <span data-ttu-id="b5e1f-120">成员</span><span class="sxs-lookup"><span data-stu-id="b5e1f-120">Member</span></span> |
| [<span data-ttu-id="b5e1f-121">addHandlerAsync</span><span class="sxs-lookup"><span data-stu-id="b5e1f-121">addHandlerAsync</span></span>](#addhandlerasynceventtype-handler-options-callback) | <span data-ttu-id="b5e1f-122">方法</span><span class="sxs-lookup"><span data-stu-id="b5e1f-122">Method</span></span> |
| [<span data-ttu-id="b5e1f-123">convertToEwsId</span><span class="sxs-lookup"><span data-stu-id="b5e1f-123">convertToEwsId</span></span>](#converttoewsiditemid-restversion--string) | <span data-ttu-id="b5e1f-124">方法</span><span class="sxs-lookup"><span data-stu-id="b5e1f-124">Method</span></span> |
| [<span data-ttu-id="b5e1f-125">convertToLocalClientTime</span><span class="sxs-lookup"><span data-stu-id="b5e1f-125">convertToLocalClientTime</span></span>](#converttolocalclienttimetimevalue--localclienttimejavascriptapioutlook15officelocalclienttime) | <span data-ttu-id="b5e1f-126">方法</span><span class="sxs-lookup"><span data-stu-id="b5e1f-126">Method</span></span> |
| [<span data-ttu-id="b5e1f-127">convertToRestId</span><span class="sxs-lookup"><span data-stu-id="b5e1f-127">convertToRestId</span></span>](#converttorestiditemid-restversion--string) | <span data-ttu-id="b5e1f-128">方法</span><span class="sxs-lookup"><span data-stu-id="b5e1f-128">Method</span></span> |
| [<span data-ttu-id="b5e1f-129">convertToUtcClientTime</span><span class="sxs-lookup"><span data-stu-id="b5e1f-129">convertToUtcClientTime</span></span>](#converttoutcclienttimeinput--date) | <span data-ttu-id="b5e1f-130">方法</span><span class="sxs-lookup"><span data-stu-id="b5e1f-130">Method</span></span> |
| [<span data-ttu-id="b5e1f-131">displayAppointmentForm</span><span class="sxs-lookup"><span data-stu-id="b5e1f-131">displayAppointmentForm</span></span>](#displayappointmentformitemid) | <span data-ttu-id="b5e1f-132">方法</span><span class="sxs-lookup"><span data-stu-id="b5e1f-132">Method</span></span> |
| [<span data-ttu-id="b5e1f-133">displayMessageForm</span><span class="sxs-lookup"><span data-stu-id="b5e1f-133">displayMessageForm</span></span>](#displaymessageformitemid) | <span data-ttu-id="b5e1f-134">方法</span><span class="sxs-lookup"><span data-stu-id="b5e1f-134">Method</span></span> |
| [<span data-ttu-id="b5e1f-135">displayNewAppointmentForm</span><span class="sxs-lookup"><span data-stu-id="b5e1f-135">displayNewAppointmentForm</span></span>](#displaynewappointmentformparameters) | <span data-ttu-id="b5e1f-136">方法</span><span class="sxs-lookup"><span data-stu-id="b5e1f-136">Method</span></span> |
| [<span data-ttu-id="b5e1f-137">getCallbackTokenAsync</span><span class="sxs-lookup"><span data-stu-id="b5e1f-137">getCallbackTokenAsync</span></span>](#getcallbacktokenasyncoptions-callback) | <span data-ttu-id="b5e1f-138">方法</span><span class="sxs-lookup"><span data-stu-id="b5e1f-138">Method</span></span> |
| [<span data-ttu-id="b5e1f-139">getCallbackTokenAsync</span><span class="sxs-lookup"><span data-stu-id="b5e1f-139">getCallbackTokenAsync</span></span>](#getcallbacktokenasynccallback-usercontext) | <span data-ttu-id="b5e1f-140">方法</span><span class="sxs-lookup"><span data-stu-id="b5e1f-140">Method</span></span> |
| [<span data-ttu-id="b5e1f-141">getUserIdentityTokenAsync</span><span class="sxs-lookup"><span data-stu-id="b5e1f-141">getUserIdentityTokenAsync</span></span>](#getuseridentitytokenasynccallback-usercontext) | <span data-ttu-id="b5e1f-142">方法</span><span class="sxs-lookup"><span data-stu-id="b5e1f-142">Method</span></span> |
| [<span data-ttu-id="b5e1f-143">makeEwsRequestAsync</span><span class="sxs-lookup"><span data-stu-id="b5e1f-143">makeEwsRequestAsync</span></span>](#makeewsrequestasyncdata-callback-usercontext) | <span data-ttu-id="b5e1f-144">方法</span><span class="sxs-lookup"><span data-stu-id="b5e1f-144">Method</span></span> |

### <a name="namespaces"></a><span data-ttu-id="b5e1f-145">命名空间</span><span class="sxs-lookup"><span data-stu-id="b5e1f-145">Namespaces</span></span>

<span data-ttu-id="b5e1f-146">[diagnostics](Office.context.mailbox.diagnostics.md)：将诊断信息提供给 Outlook 外接程序。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-146">[diagnostics](Office.context.mailbox.diagnostics.md): Provides diagnostic information to an Outlook add-in.</span></span>

<span data-ttu-id="b5e1f-147">[item](Office.context.mailbox.item.md)：提供用于访问 Outlook 外接程序中的邮件或约会的方法和属性。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-147">[item](Office.context.mailbox.item.md): Provides methods and properties for accessing a message or appointment in an Outlook add-in.</span></span>

<span data-ttu-id="b5e1f-148">[userProfile](Office.context.mailbox.userProfile.md)：提供有关 Outlook 外接程序中的用户的信息。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-148">[userProfile](Office.context.mailbox.userProfile.md): Provides information about the user in an Outlook add-in.</span></span>

### <a name="members"></a><span data-ttu-id="b5e1f-149">成员</span><span class="sxs-lookup"><span data-stu-id="b5e1f-149">Members</span></span>

#### <a name="ewsurl-string"></a><span data-ttu-id="b5e1f-150">ewsUrl :String</span><span class="sxs-lookup"><span data-stu-id="b5e1f-150">ewsUrl :String</span></span>

<span data-ttu-id="b5e1f-p102">获取此电子邮件帐户的 Exchange Web 服务 (EWS) 终结点的 URL。仅限阅读模式。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p102">Gets the URL of the Exchange Web Services (EWS) endpoint for this email account. Read mode only.</span></span>

> [!NOTE]
> <span data-ttu-id="b5e1f-153">此成员不支持适用于 iOS 的 Outlook 或 Outlook for Android。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-153">This member is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="b5e1f-p103">远程服务可使用 `ewsUrl` 值对用户邮箱进行 EWS 调用。例如，可以创建远程服务来 [获取选定项目中的附件](https://docs.microsoft.com/outlook/add-ins/get-attachments-of-an-outlook-item)。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p103">The `ewsUrl` value can be used by a remote service to make EWS calls to the user's mailbox. For example, you can create a remote service to [get attachments from the selected item](https://docs.microsoft.com/outlook/add-ins/get-attachments-of-an-outlook-item).</span></span>

<span data-ttu-id="b5e1f-156">应用必须在其清单中指定拥有 **ReadItem** 权限，才能调用阅读模式中的 `ewsUrl` 成员。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-156">Your app must have the **ReadItem** permission specified in its manifest to call the `ewsUrl` member in read mode.</span></span>

<span data-ttu-id="b5e1f-p104">在撰写模式中，必须调用 [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) 方法，才能使用 `ewsUrl` 成员。应用必须具有调用 `saveAsync` 方法的 **ReadWriteItem** 权限。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p104">In compose mode you must call the [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) method before you can use the `ewsUrl` member. Your app must have **ReadWriteItem** permissions to call the `saveAsync` method.</span></span>

##### <a name="type"></a><span data-ttu-id="b5e1f-159">类型:</span><span class="sxs-lookup"><span data-stu-id="b5e1f-159">Type:</span></span>

*   <span data-ttu-id="b5e1f-160">String</span><span class="sxs-lookup"><span data-stu-id="b5e1f-160">String</span></span>

##### <a name="requirements"></a><span data-ttu-id="b5e1f-161">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-161">Requirements</span></span>

|<span data-ttu-id="b5e1f-162">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-162">Requirement</span></span>| <span data-ttu-id="b5e1f-163">值</span><span class="sxs-lookup"><span data-stu-id="b5e1f-163">Value</span></span>|
|---|---|
|[<span data-ttu-id="b5e1f-164">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="b5e1f-164">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="b5e1f-165">1.0</span><span class="sxs-lookup"><span data-stu-id="b5e1f-165">1.0</span></span>|
|[<span data-ttu-id="b5e1f-166">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="b5e1f-166">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="b5e1f-167">ReadItem</span><span class="sxs-lookup"><span data-stu-id="b5e1f-167">ReadItem</span></span>|
|[<span data-ttu-id="b5e1f-168">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="b5e1f-168">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="b5e1f-169">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="b5e1f-169">Compose or read</span></span>|

#### <a name="resturl-string"></a><span data-ttu-id="b5e1f-170">restUrl :String</span><span class="sxs-lookup"><span data-stu-id="b5e1f-170">restUrl :String</span></span>

<span data-ttu-id="b5e1f-171">获取此电子邮件帐户的 REST 终结点的 URL。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-171">Gets the URL of the REST endpoint for this email account.</span></span>

<span data-ttu-id="b5e1f-172">`restUrl` 值可用于对用户邮箱进行 [REST API](https://docs.microsoft.com/outlook/rest/) 调用。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-172">The `restUrl` value can be used to make [REST API](https://docs.microsoft.com/outlook/rest/) calls to the user's mailbox.</span></span>

<span data-ttu-id="b5e1f-173">应用必须在其清单中指定拥有 **ReadItem** 权限，才能调用阅读模式中的 `restUrl` 成员。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-173">Your app must have the **ReadItem** permission specified in its manifest to call the `restUrl` member in read mode.</span></span>

<span data-ttu-id="b5e1f-p105">在撰写模式中，必须调用 [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) 方法，才能使用 `restUrl` 成员。应用必须具有调用 `saveAsync` 方法的 **ReadWriteItem** 权限。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p105">In compose mode you must call the [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) method before you can use the `restUrl` member. Your app must have **ReadWriteItem** permissions to call the `saveAsync` method.</span></span>

> [!NOTE]
> <span data-ttu-id="b5e1f-176">连接到 Exchange 2016 与自定义配置的 REST URL 的本地安装的 outlook 客户端将返回值无效`restUrl`。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-176">Outlook clients connected to on-premises installations of Exchange 2016 with a custom REST URL configured will return an invalid value for `restUrl`.</span></span>

##### <a name="type"></a><span data-ttu-id="b5e1f-177">类型:</span><span class="sxs-lookup"><span data-stu-id="b5e1f-177">Type:</span></span>

*   <span data-ttu-id="b5e1f-178">String</span><span class="sxs-lookup"><span data-stu-id="b5e1f-178">String</span></span>

##### <a name="requirements"></a><span data-ttu-id="b5e1f-179">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-179">Requirements</span></span>

|<span data-ttu-id="b5e1f-180">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-180">Requirement</span></span>| <span data-ttu-id="b5e1f-181">值</span><span class="sxs-lookup"><span data-stu-id="b5e1f-181">Value</span></span>|
|---|---|
|[<span data-ttu-id="b5e1f-182">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="b5e1f-182">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="b5e1f-183">1.5</span><span class="sxs-lookup"><span data-stu-id="b5e1f-183">1.5</span></span> |
|[<span data-ttu-id="b5e1f-184">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="b5e1f-184">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="b5e1f-185">ReadItem</span><span class="sxs-lookup"><span data-stu-id="b5e1f-185">ReadItem</span></span>|
|[<span data-ttu-id="b5e1f-186">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="b5e1f-186">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="b5e1f-187">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="b5e1f-187">Compose or read</span></span>|

### <a name="methods"></a><span data-ttu-id="b5e1f-188">方法</span><span class="sxs-lookup"><span data-stu-id="b5e1f-188">Methods</span></span>

####  <a name="addhandlerasynceventtype-handler-options-callback"></a><span data-ttu-id="b5e1f-189">addHandlerAsync(eventType, handler, [options], [callback])</span><span class="sxs-lookup"><span data-stu-id="b5e1f-189">addHandlerAsync(eventType, handler, [options], [callback])</span></span>

<span data-ttu-id="b5e1f-190">添加支持事件的事件处理程序。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-190">Adds an event handler for a supported event.</span></span>

<span data-ttu-id="b5e1f-p106">目前，唯一受支持的事件类型是 `Office.EventType.ItemChanged`，用户选择一个新项目时将调用该类型。此事件由实现可固定任务窗格的外接程序使用，并允许外接程序根据当前选定的项目刷新任务窗格 UI。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p106">Currently the only supported event type is `Office.EventType.ItemChanged`, which is invoked when the user selects a new item. This event is used by add-ins that implement a pinnable taskpane, and allows the add-in to refresh the taskpane UI based on the currently selected item.</span></span>

##### <a name="parameters"></a><span data-ttu-id="b5e1f-193">参数：</span><span class="sxs-lookup"><span data-stu-id="b5e1f-193">Parameters:</span></span>

| <span data-ttu-id="b5e1f-194">名称</span><span class="sxs-lookup"><span data-stu-id="b5e1f-194">Name</span></span> | <span data-ttu-id="b5e1f-195">类型</span><span class="sxs-lookup"><span data-stu-id="b5e1f-195">Type</span></span> | <span data-ttu-id="b5e1f-196">属性</span><span class="sxs-lookup"><span data-stu-id="b5e1f-196">Attributes</span></span> | <span data-ttu-id="b5e1f-197">说明</span><span class="sxs-lookup"><span data-stu-id="b5e1f-197">Description</span></span> |
|---|---|---|---|
| `eventType` | [<span data-ttu-id="b5e1f-198">Office.EventType</span><span class="sxs-lookup"><span data-stu-id="b5e1f-198">Office.EventType</span></span>](office.md#eventtype-string) || <span data-ttu-id="b5e1f-199">应调用处理程序的事件。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-199">The event that should invoke the handler.</span></span> |
| `handler` | <span data-ttu-id="b5e1f-200">函数</span><span class="sxs-lookup"><span data-stu-id="b5e1f-200">Function</span></span> || <span data-ttu-id="b5e1f-p107">用于处理事件的函数。此函数必须接受一个参数，即对象文本。参数上的 `type` 属性将匹配传递给 `addHandlerAsync` 的 `eventType` 参数。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p107">The function to handle the event. The function must accept a single parameter, which is an object literal. The `type` property on the parameter will match the `eventType` parameter passed to `addHandlerAsync`.</span></span> |
| `options` | <span data-ttu-id="b5e1f-204">Object</span><span class="sxs-lookup"><span data-stu-id="b5e1f-204">Object</span></span> | <span data-ttu-id="b5e1f-205">&lt;可选&gt;</span><span class="sxs-lookup"><span data-stu-id="b5e1f-205">&lt;optional&gt;</span></span> | <span data-ttu-id="b5e1f-206">包含一个或多个以下属性的对象文本。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-206">An object literal that contains one or more of the following properties.</span></span> |
| `options.asyncContext` | <span data-ttu-id="b5e1f-207">对象</span><span class="sxs-lookup"><span data-stu-id="b5e1f-207">Object</span></span> | <span data-ttu-id="b5e1f-208">&lt;可选&gt;</span><span class="sxs-lookup"><span data-stu-id="b5e1f-208">&lt;optional&gt;</span></span> | <span data-ttu-id="b5e1f-209">开发人员可以提供他们想要在回调方法中访问的任何对象。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-209">Developers can provide any object they wish to access in the callback method.</span></span> |
| `callback` | <span data-ttu-id="b5e1f-210">函数</span><span class="sxs-lookup"><span data-stu-id="b5e1f-210">function</span></span>| <span data-ttu-id="b5e1f-211">&lt;可选&gt;</span><span class="sxs-lookup"><span data-stu-id="b5e1f-211">&lt;optional&gt;</span></span>|<span data-ttu-id="b5e1f-212">方法完成后，使用单个参数 `callback`（一个 [`asyncResult`](/javascript/api/office/office.asyncresult) 对象）调用在 `AsyncResult` 参数中传递的函数。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-212">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="b5e1f-213">Requirements</span><span class="sxs-lookup"><span data-stu-id="b5e1f-213">Requirements</span></span>

|<span data-ttu-id="b5e1f-214">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-214">Requirement</span></span>| <span data-ttu-id="b5e1f-215">值</span><span class="sxs-lookup"><span data-stu-id="b5e1f-215">Value</span></span>|
|---|---|
|[<span data-ttu-id="b5e1f-216">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="b5e1f-216">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="b5e1f-217">1.5</span><span class="sxs-lookup"><span data-stu-id="b5e1f-217">1.5</span></span> |
|[<span data-ttu-id="b5e1f-218">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="b5e1f-218">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="b5e1f-219">ReadItem</span><span class="sxs-lookup"><span data-stu-id="b5e1f-219">ReadItem</span></span> |
|[<span data-ttu-id="b5e1f-220">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="b5e1f-220">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="b5e1f-221">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="b5e1f-221">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="b5e1f-222">示例</span><span class="sxs-lookup"><span data-stu-id="b5e1f-222">Example</span></span>

```
Office.initialize = function (reason) {
  $(document).ready(function () {
    Office.context.mailbox.addHandlerAsync(Office.EventType.ItemChanged, loadNewItem, function (result) {
      if (result.status === Office.AsyncResultStatus.Failed) {
        // Handle error
      }
    });
  });
};

function loadNewItem(eventArgs) {
  // Load the properties of the newly selected item
  loadProps(Office.context.mailbox.item);
};
```

####  <a name="converttoewsiditemid-restversion--string"></a><span data-ttu-id="b5e1f-223">convertToEwsId(itemId, restVersion) → {String}</span><span class="sxs-lookup"><span data-stu-id="b5e1f-223">convertToEwsId(itemId, restVersion) → {String}</span></span>

<span data-ttu-id="b5e1f-224">将项目 ID 格式化（从 REST 转换为 EWS 格式）。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-224">Converts an item ID formatted for REST into EWS format.</span></span>

> [!NOTE]
> <span data-ttu-id="b5e1f-225">在适用于 iOS 的 Outlook 或 Outlook for Android 中不支持此方法。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-225">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="b5e1f-p108">通过 REST API 检索的项 ID（如 [Outlook 邮件 API](https://docs.microsoft.com/previous-versions/office/office-365-api/api/version-2.0/mail-rest-operations) 或 [Microsoft Graph](http://graph.microsoft.io/)）使用与 Exchange Web 服务 (EWS) 所使用格式不同的格式。`convertToEwsId` 方法将 REST 格式化的 ID 转换为正确的 EWS 格式。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p108">Item IDs retrieved via a REST API (such as the [Outlook Mail API](https://docs.microsoft.com/previous-versions/office/office-365-api/api/version-2.0/mail-rest-operations) or the [Microsoft Graph](http://graph.microsoft.io/)) use a different format than the format used by Exchange Web Services (EWS). The `convertToEwsId` method converts a REST-formatted ID into the proper format for EWS.</span></span>

##### <a name="parameters"></a><span data-ttu-id="b5e1f-228">参数：</span><span class="sxs-lookup"><span data-stu-id="b5e1f-228">Parameters:</span></span>

|<span data-ttu-id="b5e1f-229">名称</span><span class="sxs-lookup"><span data-stu-id="b5e1f-229">Name</span></span>| <span data-ttu-id="b5e1f-230">类型</span><span class="sxs-lookup"><span data-stu-id="b5e1f-230">Type</span></span>| <span data-ttu-id="b5e1f-231">说明</span><span class="sxs-lookup"><span data-stu-id="b5e1f-231">Description</span></span>|
|---|---|---|
|`itemId`| <span data-ttu-id="b5e1f-232">字符串</span><span class="sxs-lookup"><span data-stu-id="b5e1f-232">String</span></span>|<span data-ttu-id="b5e1f-233">Outlook REST API 的格式化的项目 ID。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-233">An item ID formatted for the Outlook REST APIs</span></span>|
|`restVersion`| [<span data-ttu-id="b5e1f-234">Office.MailboxEnums.RestVersion</span><span class="sxs-lookup"><span data-stu-id="b5e1f-234">Office.MailboxEnums.RestVersion</span></span>](/javascript/api/outlook_1_5/office.mailboxenums.restversion)|<span data-ttu-id="b5e1f-235">指示用于检索项目 ID 的 Outlook REST API 的版本。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-235">A value indicating the version of the Outlook REST API used to retrieve the item ID.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="b5e1f-236">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-236">Requirements</span></span>

|<span data-ttu-id="b5e1f-237">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-237">Requirement</span></span>| <span data-ttu-id="b5e1f-238">值</span><span class="sxs-lookup"><span data-stu-id="b5e1f-238">Value</span></span>|
|---|---|
|[<span data-ttu-id="b5e1f-239">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="b5e1f-239">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="b5e1f-240">1.3</span><span class="sxs-lookup"><span data-stu-id="b5e1f-240">1.3</span></span>|
|[<span data-ttu-id="b5e1f-241">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="b5e1f-241">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="b5e1f-242">受限</span><span class="sxs-lookup"><span data-stu-id="b5e1f-242">Restricted</span></span>|
|[<span data-ttu-id="b5e1f-243">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="b5e1f-243">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="b5e1f-244">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="b5e1f-244">Compose or read</span></span>|

##### <a name="returns"></a><span data-ttu-id="b5e1f-245">返回：</span><span class="sxs-lookup"><span data-stu-id="b5e1f-245">Returns:</span></span>

<span data-ttu-id="b5e1f-246">类型：字符串</span><span class="sxs-lookup"><span data-stu-id="b5e1f-246">Type: String</span></span>

##### <a name="example"></a><span data-ttu-id="b5e1f-247">示例</span><span class="sxs-lookup"><span data-stu-id="b5e1f-247">Example</span></span>

```
// Get an item's ID from a REST API
var restId = 'AAMkAGVlOTZjNTM3LW...';

// Treat restId as coming from the v2.0 version of the
// Outlook Mail API
var ewsId = Office.context.mailbox.convertToEwsId(restId, Office.MailboxEnums.RestVersion.v2_0);
```

####  <a name="converttolocalclienttimetimevalue--localclienttimejavascriptapioutlook15officelocalclienttime"></a><span data-ttu-id="b5e1f-248">convertToLocalClientTime(timeValue) → {[LocalClientTime](/javascript/api/outlook_1_5/office.LocalClientTime)}</span><span class="sxs-lookup"><span data-stu-id="b5e1f-248">convertToLocalClientTime(timeValue) → {[LocalClientTime](/javascript/api/outlook_1_5/office.LocalClientTime)}</span></span>

<span data-ttu-id="b5e1f-249">获取包含以本地客户端时间表示的时间信息的字典。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-249">Gets a dictionary containing time information in local client time.</span></span>

<span data-ttu-id="b5e1f-p109">Outlook 或 Outlook Web App 邮件应用程序的日期和时间可以使用不同的时区。Outlook 使用客户端计算机时区；Outlook Web App 使用 Exchange 管理中心 (EAC) 中设置的时区。应对日期和时间值进行处理，以便用户界面上显示的值始终与用户预期的时区一致。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p109">The dates and times used by a mail app for Outlook or Outlook Web App can use different time zones. Outlook uses the client computer time zone; Outlook Web App uses the time zone set on the Exchange Admin Center (EAC). You should handle date and time values so that the values you display on the user interface are always consistent with the time zone that the user expects.</span></span>

<span data-ttu-id="b5e1f-p110">如果邮件应用程序在 Outlook 中运行，`convertToLocalClientTime` 方法将返回一个值设置为客户端计算机时区的字典对象。如果邮件应用程序在 Outlook Web App 中运行，`convertToLocalClientTime` 方法将返回值设置为 EAC 中指定的时区的字典对象。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p110">If the mail app is running in Outlook, the `convertToLocalClientTime` method will return a dictionary object with the values set to the client computer time zone. If the mail app is running in Outlook Web App, the `convertToLocalClientTime` method will return a dictionary object with the values set to the time zone specified in the EAC.</span></span>

##### <a name="parameters"></a><span data-ttu-id="b5e1f-255">参数：</span><span class="sxs-lookup"><span data-stu-id="b5e1f-255">Parameters:</span></span>

|<span data-ttu-id="b5e1f-256">名称</span><span class="sxs-lookup"><span data-stu-id="b5e1f-256">Name</span></span>| <span data-ttu-id="b5e1f-257">类型</span><span class="sxs-lookup"><span data-stu-id="b5e1f-257">Type</span></span>| <span data-ttu-id="b5e1f-258">说明</span><span class="sxs-lookup"><span data-stu-id="b5e1f-258">Description</span></span>|
|---|---|---|
|`timeValue`| <span data-ttu-id="b5e1f-259">日期</span><span class="sxs-lookup"><span data-stu-id="b5e1f-259">Date</span></span>|<span data-ttu-id="b5e1f-260">一个 Date 对象</span><span class="sxs-lookup"><span data-stu-id="b5e1f-260">A Date object</span></span>|

##### <a name="requirements"></a><span data-ttu-id="b5e1f-261">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-261">Requirements</span></span>

|<span data-ttu-id="b5e1f-262">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-262">Requirement</span></span>| <span data-ttu-id="b5e1f-263">值</span><span class="sxs-lookup"><span data-stu-id="b5e1f-263">Value</span></span>|
|---|---|
|[<span data-ttu-id="b5e1f-264">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="b5e1f-264">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="b5e1f-265">1.0</span><span class="sxs-lookup"><span data-stu-id="b5e1f-265">1.0</span></span>|
|[<span data-ttu-id="b5e1f-266">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="b5e1f-266">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="b5e1f-267">ReadItem</span><span class="sxs-lookup"><span data-stu-id="b5e1f-267">ReadItem</span></span>|
|[<span data-ttu-id="b5e1f-268">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="b5e1f-268">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="b5e1f-269">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="b5e1f-269">Compose or read</span></span>|

##### <a name="returns"></a><span data-ttu-id="b5e1f-270">返回：</span><span class="sxs-lookup"><span data-stu-id="b5e1f-270">Returns:</span></span>

<span data-ttu-id="b5e1f-271">类型：[LocalClientTime](/javascript/api/outlook_1_5/office.LocalClientTime)</span><span class="sxs-lookup"><span data-stu-id="b5e1f-271">Type: [LocalClientTime](/javascript/api/outlook_1_5/office.LocalClientTime)</span></span>

####  <a name="converttorestiditemid-restversion--string"></a><span data-ttu-id="b5e1f-272">convertToRestId(itemId, restVersion) → {String}</span><span class="sxs-lookup"><span data-stu-id="b5e1f-272">convertToRestId(itemId, restVersion) → {String}</span></span>

<span data-ttu-id="b5e1f-273">将项目 ID 格式化（从 EWS 转换为 REST 格式）。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-273">Converts an item ID formatted for EWS into REST format.</span></span>

> [!NOTE]
> <span data-ttu-id="b5e1f-274">在适用于 iOS 的 Outlook 或 Outlook for Android 中不支持此方法。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-274">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="b5e1f-p111">与 REST API 所使用的格式比较，通过 EWS 或通过 `itemId` 属性检索的项目 ID 使用不同的格式（例如 [Outlook Mail API](https://docs.microsoft.com/previous-versions/office/office-365-api/api/version-2.0/mail-rest-operations) 或 [Microsoft Graph](http://graph.microsoft.io/)）。`convertToRestId` 方法将 EWS 格式化的 ID 转换为正确的 REST 格式。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p111">Item IDs retrieved via EWS or via the `itemId` property use a different format than the format used by REST APIs (such as the [Outlook Mail API](https://docs.microsoft.com/previous-versions/office/office-365-api/api/version-2.0/mail-rest-operations) or the [Microsoft Graph](http://graph.microsoft.io/)). The `convertToRestId` method converts an EWS-formatted ID into the proper format for REST.</span></span>

##### <a name="parameters"></a><span data-ttu-id="b5e1f-277">参数：</span><span class="sxs-lookup"><span data-stu-id="b5e1f-277">Parameters:</span></span>

|<span data-ttu-id="b5e1f-278">名称</span><span class="sxs-lookup"><span data-stu-id="b5e1f-278">Name</span></span>| <span data-ttu-id="b5e1f-279">类型</span><span class="sxs-lookup"><span data-stu-id="b5e1f-279">Type</span></span>| <span data-ttu-id="b5e1f-280">说明</span><span class="sxs-lookup"><span data-stu-id="b5e1f-280">Description</span></span>|
|---|---|---|
|`itemId`| <span data-ttu-id="b5e1f-281">字符串</span><span class="sxs-lookup"><span data-stu-id="b5e1f-281">String</span></span>|<span data-ttu-id="b5e1f-282">适用于 Exchange Web 服务 (EWS) 的项目 ID 格式化。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-282">An item ID formatted for Exchange Web Services (EWS)</span></span>|
|`restVersion`| [<span data-ttu-id="b5e1f-283">Office.MailboxEnums.RestVersion</span><span class="sxs-lookup"><span data-stu-id="b5e1f-283">Office.MailboxEnums.RestVersion</span></span>](/javascript/api/outlook_1_5/office.mailboxenums.restversion)|<span data-ttu-id="b5e1f-284">值指示转换的 ID 所使用的 Outlook REST API 的版本。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-284">A value indicating the version of the Outlook REST API that the converted ID will be used with.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="b5e1f-285">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-285">Requirements</span></span>

|<span data-ttu-id="b5e1f-286">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-286">Requirement</span></span>| <span data-ttu-id="b5e1f-287">值</span><span class="sxs-lookup"><span data-stu-id="b5e1f-287">Value</span></span>|
|---|---|
|[<span data-ttu-id="b5e1f-288">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="b5e1f-288">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="b5e1f-289">1.3</span><span class="sxs-lookup"><span data-stu-id="b5e1f-289">1.3</span></span>|
|[<span data-ttu-id="b5e1f-290">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="b5e1f-290">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="b5e1f-291">受限</span><span class="sxs-lookup"><span data-stu-id="b5e1f-291">Restricted</span></span>|
|[<span data-ttu-id="b5e1f-292">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="b5e1f-292">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="b5e1f-293">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="b5e1f-293">Compose or read</span></span>|

##### <a name="returns"></a><span data-ttu-id="b5e1f-294">返回：</span><span class="sxs-lookup"><span data-stu-id="b5e1f-294">Returns:</span></span>

<span data-ttu-id="b5e1f-295">类型：字符串</span><span class="sxs-lookup"><span data-stu-id="b5e1f-295">Type: String</span></span>

##### <a name="example"></a><span data-ttu-id="b5e1f-296">示例</span><span class="sxs-lookup"><span data-stu-id="b5e1f-296">Example</span></span>

```
// Get the currently selected item's ID
var ewsId = Office.context.mailbox.item.itemId;

// Convert to a REST ID for the v2.0 version of the
// Outlook Mail API
var restId = Office.context.mailbox.convertToRestId(ewsId, Office.MailboxEnums.RestVersion.v2_0);
```

####  <a name="converttoutcclienttimeinput--date"></a><span data-ttu-id="b5e1f-297">convertToUtcClientTime(input) → {Date}</span><span class="sxs-lookup"><span data-stu-id="b5e1f-297">convertToUtcClientTime(input) → {Date}</span></span>

<span data-ttu-id="b5e1f-298">从包含时间信息的字典中获取 Date 对象。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-298">Gets a Date object from a dictionary containing time information.</span></span>

<span data-ttu-id="b5e1f-299">`convertToUtcClientTime` 方法将包含本地日期和时间的字典转换为包含与本地日期和时间对应的正确值的 Date 对象。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-299">The `convertToUtcClientTime` method converts a dictionary containing a local date and time to a Date object with the correct values for the local date and time.</span></span>

##### <a name="parameters"></a><span data-ttu-id="b5e1f-300">参数：</span><span class="sxs-lookup"><span data-stu-id="b5e1f-300">Parameters:</span></span>

|<span data-ttu-id="b5e1f-301">名称</span><span class="sxs-lookup"><span data-stu-id="b5e1f-301">Name</span></span>| <span data-ttu-id="b5e1f-302">类型</span><span class="sxs-lookup"><span data-stu-id="b5e1f-302">Type</span></span>| <span data-ttu-id="b5e1f-303">说明</span><span class="sxs-lookup"><span data-stu-id="b5e1f-303">Description</span></span>|
|---|---|---|
|`input`| [<span data-ttu-id="b5e1f-304">LocalClientTime</span><span class="sxs-lookup"><span data-stu-id="b5e1f-304">LocalClientTime</span></span>](/javascript/api/outlook_1_5/office.LocalClientTime)|<span data-ttu-id="b5e1f-305">要转换的本地时间值。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-305">The local time value to convert.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="b5e1f-306">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-306">Requirements</span></span>

|<span data-ttu-id="b5e1f-307">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-307">Requirement</span></span>| <span data-ttu-id="b5e1f-308">值</span><span class="sxs-lookup"><span data-stu-id="b5e1f-308">Value</span></span>|
|---|---|
|[<span data-ttu-id="b5e1f-309">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="b5e1f-309">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="b5e1f-310">1.0</span><span class="sxs-lookup"><span data-stu-id="b5e1f-310">1.0</span></span>|
|[<span data-ttu-id="b5e1f-311">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="b5e1f-311">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="b5e1f-312">ReadItem</span><span class="sxs-lookup"><span data-stu-id="b5e1f-312">ReadItem</span></span>|
|[<span data-ttu-id="b5e1f-313">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="b5e1f-313">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="b5e1f-314">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="b5e1f-314">Compose or read</span></span>|

##### <a name="returns"></a><span data-ttu-id="b5e1f-315">返回：</span><span class="sxs-lookup"><span data-stu-id="b5e1f-315">Returns:</span></span>

<span data-ttu-id="b5e1f-316">包含以 UTC 表示的时间的 Date 对象。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-316">A Date object with the time expressed in UTC.</span></span>

<dl class="param-type"><span data-ttu-id="b5e1f-317">

<dt>
类型</dt>


</span><span class="sxs-lookup"><span data-stu-id="b5e1f-317">

<dt>Type</dt>

</span></span><dd><span data-ttu-id="b5e1f-318">日期</span><span class="sxs-lookup"><span data-stu-id="b5e1f-318">Date</span></span></dd>

</dl>

####  <a name="displayappointmentformitemid"></a><span data-ttu-id="b5e1f-319">displayAppointmentForm(itemId)</span><span class="sxs-lookup"><span data-stu-id="b5e1f-319">displayAppointmentForm(itemId)</span></span>

<span data-ttu-id="b5e1f-320">显示现有日历约会。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-320">Displays an existing calendar appointment.</span></span>

> [!NOTE]
> <span data-ttu-id="b5e1f-321">在适用于 iOS 的 Outlook 或 Outlook for Android 中不支持此方法。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-321">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="b5e1f-322">`displayAppointmentForm` 方法将打开桌面新窗口中或移动设备对话框中的现有日历约会。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-322">The `displayAppointmentForm` method opens an existing calendar appointment in a new window on the desktop or in a dialog box on mobile devices.</span></span>

<span data-ttu-id="b5e1f-p112">在 Outlook for Mac 中，您可以使用此方法来显示不属于定期系列的单个约会，或显示定期系列的主约会，但无法显示该系列的实例。这是因为在 Outlook for Mac 中，无法访问定期系列实例的属性（包括项目 ID）。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p112">In Outlook for Mac, you can use this method to display a single appointment that is not part of a recurring series, or the master appointment of a recurring series, but you cannot display an instance of the series. This is because in Outlook for Mac, you cannot access the properties (including the item ID) of instances of a recurring series.</span></span>

<span data-ttu-id="b5e1f-325">在 Outlook Web App 中，此方法仅在窗体正文小于或等于 32KB 字符数时，才会打开指定的窗体。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-325">In Outlook Web App, this method opens the specified form only if the body of the form is less than or equal to 32KB number of characters.</span></span>

<span data-ttu-id="b5e1f-326">如果指定的项标识符没有识别现有约会，将在客户端计算机或设备上打开一个空白窗格，并且不会返回错误消息。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-326">If the specified item identifier does not identify an existing appointment, a blank pane opens on the client computer or device, and no error message will be returned.</span></span>

##### <a name="parameters"></a><span data-ttu-id="b5e1f-327">参数：</span><span class="sxs-lookup"><span data-stu-id="b5e1f-327">Parameters:</span></span>

|<span data-ttu-id="b5e1f-328">名称</span><span class="sxs-lookup"><span data-stu-id="b5e1f-328">Name</span></span>| <span data-ttu-id="b5e1f-329">类型</span><span class="sxs-lookup"><span data-stu-id="b5e1f-329">Type</span></span>| <span data-ttu-id="b5e1f-330">说明</span><span class="sxs-lookup"><span data-stu-id="b5e1f-330">Description</span></span>|
|---|---|---|
|`itemId`| <span data-ttu-id="b5e1f-331">字符串</span><span class="sxs-lookup"><span data-stu-id="b5e1f-331">String</span></span>|<span data-ttu-id="b5e1f-332">现有日历约会的 Exchange Web 服务 (EWS) 标识符。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-332">The Exchange Web Services (EWS) identifier for an existing calendar appointment.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="b5e1f-333">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-333">Requirements</span></span>

|<span data-ttu-id="b5e1f-334">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-334">Requirement</span></span>| <span data-ttu-id="b5e1f-335">值</span><span class="sxs-lookup"><span data-stu-id="b5e1f-335">Value</span></span>|
|---|---|
|[<span data-ttu-id="b5e1f-336">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="b5e1f-336">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="b5e1f-337">1.0</span><span class="sxs-lookup"><span data-stu-id="b5e1f-337">1.0</span></span>|
|[<span data-ttu-id="b5e1f-338">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="b5e1f-338">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="b5e1f-339">ReadItem</span><span class="sxs-lookup"><span data-stu-id="b5e1f-339">ReadItem</span></span>|
|[<span data-ttu-id="b5e1f-340">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="b5e1f-340">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="b5e1f-341">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="b5e1f-341">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="b5e1f-342">示例</span><span class="sxs-lookup"><span data-stu-id="b5e1f-342">Example</span></span>

```
Office.context.mailbox.displayAppointmentForm(appointmentId);
```

####  <a name="displaymessageformitemid"></a><span data-ttu-id="b5e1f-343">displayMessageForm(itemId)</span><span class="sxs-lookup"><span data-stu-id="b5e1f-343">displayMessageForm(itemId)</span></span>

<span data-ttu-id="b5e1f-344">显示现有邮件。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-344">Displays an existing message.</span></span>

> [!NOTE]
> <span data-ttu-id="b5e1f-345">在适用于 iOS 的 Outlook 或 Outlook for Android 中不支持此方法。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-345">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="b5e1f-346">`displayMessageForm` 方法将打开桌面新窗口中或移动设备对话框中的现有邮件。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-346">The `displayMessageForm` method opens an existing message in a new window on the desktop or in a dialog box on mobile devices.</span></span>

<span data-ttu-id="b5e1f-347">在 Outlook Web App 中，此方法仅在窗体正文小于或等于 32 KB 字符数时，才会打开指定的窗体。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-347">In Outlook Web App, this method opens the specified form only if the body of the form is less than or equal to 32 KB number of characters.</span></span>

<span data-ttu-id="b5e1f-348">如果指定的项标识符未识别现有消息，则客户端计算机上不会显示任何消息，并且也不会返回错误消息。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-348">If the specified item identifier does not identify an existing message, no message will be displayed on the client computer, and no error message will be returned.</span></span>

<span data-ttu-id="b5e1f-p113">不要使用包含表示约会的 `itemId` 的 `displayMessageForm`。使用 `displayAppointmentForm` 方法显示现有的约会，并使用 `displayNewAppointmentForm` 显示窗体以新建约会。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p113">Do not use the `displayMessageForm` with an `itemId` that represents an appointment. Use the `displayAppointmentForm` method to display an existing appointment, and `displayNewAppointmentForm` to display a form to create a new appointment.</span></span>

##### <a name="parameters"></a><span data-ttu-id="b5e1f-351">参数：</span><span class="sxs-lookup"><span data-stu-id="b5e1f-351">Parameters:</span></span>

|<span data-ttu-id="b5e1f-352">名称</span><span class="sxs-lookup"><span data-stu-id="b5e1f-352">Name</span></span>| <span data-ttu-id="b5e1f-353">类型</span><span class="sxs-lookup"><span data-stu-id="b5e1f-353">Type</span></span>| <span data-ttu-id="b5e1f-354">说明</span><span class="sxs-lookup"><span data-stu-id="b5e1f-354">Description</span></span>|
|---|---|---|
|`itemId`| <span data-ttu-id="b5e1f-355">字符串</span><span class="sxs-lookup"><span data-stu-id="b5e1f-355">String</span></span>|<span data-ttu-id="b5e1f-356">现有消息的 Exchange Web 服务 (EWS) 标识符。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-356">The Exchange Web Services (EWS) identifier for an existing message.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="b5e1f-357">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-357">Requirements</span></span>

|<span data-ttu-id="b5e1f-358">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-358">Requirement</span></span>| <span data-ttu-id="b5e1f-359">值</span><span class="sxs-lookup"><span data-stu-id="b5e1f-359">Value</span></span>|
|---|---|
|[<span data-ttu-id="b5e1f-360">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="b5e1f-360">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="b5e1f-361">1.0</span><span class="sxs-lookup"><span data-stu-id="b5e1f-361">1.0</span></span>|
|[<span data-ttu-id="b5e1f-362">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="b5e1f-362">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="b5e1f-363">ReadItem</span><span class="sxs-lookup"><span data-stu-id="b5e1f-363">ReadItem</span></span>|
|[<span data-ttu-id="b5e1f-364">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="b5e1f-364">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="b5e1f-365">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="b5e1f-365">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="b5e1f-366">示例</span><span class="sxs-lookup"><span data-stu-id="b5e1f-366">Example</span></span>

```
Office.context.mailbox.displayMessageForm(messageId);
```

#### <a name="displaynewappointmentformparameters"></a><span data-ttu-id="b5e1f-367">displayNewAppointmentForm(parameters)</span><span class="sxs-lookup"><span data-stu-id="b5e1f-367">displayNewAppointmentForm(parameters)</span></span>

<span data-ttu-id="b5e1f-368">显示用于新建日历约会的表单。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-368">Displays a form for creating a new calendar appointment.</span></span>

> [!NOTE]
> <span data-ttu-id="b5e1f-369">在适用于 iOS 的 Outlook 或 Outlook for Android 中不支持此方法。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-369">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="b5e1f-p114">`displayNewAppointmentForm` 方法打开可让用户新建约会或会议的窗体。如果指定了参数，将使用参数的内容自动填充约会窗体字段。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p114">The `displayNewAppointmentForm` method opens a form that enables the user to create a new appointment or meeting. If parameters are specified, the appointment form fields are automatically populated with the contents of the parameters.</span></span>

<span data-ttu-id="b5e1f-p115">在 Outlook Web App 和适用于设备的 OWA 中，此方法始终显示包含与会者字段的窗体。如果你未将任何与会者指定为输入参数，该方法将显示为一个包含“**保存**”按钮的窗体。如果已指定与会者，窗体将包含与会者和“**发送**”按钮。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p115">In Outlook Web App and OWA for Devices, this method always displays a form with an attendees field. If you do not specify any attendees as input arguments, the method displays a form with a **Save** button. If you have specified attendees, the form would include the attendees and a **Send** button.</span></span>

<span data-ttu-id="b5e1f-p116">在 Outlook 富客户端和 Outlook RT 中，如果在 `requiredAttendees`、`optionalAttendees` 或 `resources` 参数中指定任何与会者或资源，此方法将显示会议窗体，其中包含一个“**发送**”按钮。如果未指定任何收件人，此方法将显示一个包含“**保存并关闭**”按钮的约会窗体。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p116">In the Outlook rich client and Outlook RT, if you specify any attendees or resources in the `requiredAttendees`, `optionalAttendees`, or `resources` parameter, this method displays a meeting form with a **Send** button. If you don't specify any recipients, this method displays an appointment form with a **Save & Close** button.</span></span>

<span data-ttu-id="b5e1f-377">如果任何参数超过指定大小限制，或者指定了未知参数名称，则会引发异常。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-377">If any of the parameters exceed the specified size limits, or if an unknown parameter name is specified, an exception is thrown.</span></span>

##### <a name="parameters"></a><span data-ttu-id="b5e1f-378">参数：</span><span class="sxs-lookup"><span data-stu-id="b5e1f-378">Parameters:</span></span>

|<span data-ttu-id="b5e1f-379">名称</span><span class="sxs-lookup"><span data-stu-id="b5e1f-379">Name</span></span>| <span data-ttu-id="b5e1f-380">类型</span><span class="sxs-lookup"><span data-stu-id="b5e1f-380">Type</span></span>| <span data-ttu-id="b5e1f-381">说明</span><span class="sxs-lookup"><span data-stu-id="b5e1f-381">Description</span></span>|
|---|---|---|
| `parameters` | <span data-ttu-id="b5e1f-382">对象</span><span class="sxs-lookup"><span data-stu-id="b5e1f-382">Object</span></span> | <span data-ttu-id="b5e1f-383">描述新约会的参数字典。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-383">A dictionary of parameters describing the new appointment.</span></span> |
| `parameters.requiredAttendees` | <span data-ttu-id="b5e1f-384">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)&gt;</span><span class="sxs-lookup"><span data-stu-id="b5e1f-384">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)&gt;</span></span> | <span data-ttu-id="b5e1f-p117">包含电子邮件地址的字符串数组或包含约会的每个必需与会者的 `EmailAddressDetails` 对象的数组。数组限制为最多 100 个条目。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p117">An array of strings containing the email addresses or an array containing an `EmailAddressDetails` object for each of the required attendees for the appointment. The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.optionalAttendees` | <span data-ttu-id="b5e1f-387">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)&gt;</span><span class="sxs-lookup"><span data-stu-id="b5e1f-387">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)&gt;</span></span> | <span data-ttu-id="b5e1f-p118">包含电子邮件地址的字符串数组或包含约会的每个可选与会者的 `EmailAddressDetails` 对象的数组。数组限制为最多 100 个条目。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p118">An array of strings containing the email addresses or an array containing an `EmailAddressDetails` object for each of the optional attendees for the appointment. The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.start` | <span data-ttu-id="b5e1f-390">Date</span><span class="sxs-lookup"><span data-stu-id="b5e1f-390">Date</span></span> | <span data-ttu-id="b5e1f-391">指定约会的开始日期和时间的 `Date` 对象。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-391">A `Date` object specifying the start date and time of the appointment.</span></span> |
| `parameters.end` | <span data-ttu-id="b5e1f-392">Date</span><span class="sxs-lookup"><span data-stu-id="b5e1f-392">Date</span></span> | <span data-ttu-id="b5e1f-393">指定约会的结束日期和时间的 `Date` 对象。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-393">A `Date` object specifying the end date and time of the appointment.</span></span> |
| `parameters.location` | <span data-ttu-id="b5e1f-394">String</span><span class="sxs-lookup"><span data-stu-id="b5e1f-394">String</span></span> | <span data-ttu-id="b5e1f-p119">包含约会位置的字符串。字符串长度限制为最多 255 个字符。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p119">A string containing the location of the appointment. The string is limited to a maximum of 255 characters.</span></span> |
| `parameters.resources` | <span data-ttu-id="b5e1f-397">Array.&lt;String&gt;</span><span class="sxs-lookup"><span data-stu-id="b5e1f-397">Array.&lt;String&gt;</span></span> | <span data-ttu-id="b5e1f-p120">包含约会所需资源的字符串数组。数组限制为最多 100 个条目。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p120">An array of strings containing the resources required for the appointment. The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.subject` | <span data-ttu-id="b5e1f-400">String</span><span class="sxs-lookup"><span data-stu-id="b5e1f-400">String</span></span> | <span data-ttu-id="b5e1f-p121">包含约会主题的字符串。字符串长度限制为最多 255 个字符。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p121">A string containing the subject of the appointment. The string is limited to a maximum of 255 characters.</span></span> |
| `parameters.body` | <span data-ttu-id="b5e1f-403">String</span><span class="sxs-lookup"><span data-stu-id="b5e1f-403">String</span></span> | <span data-ttu-id="b5e1f-p122">约会的正文。正文内容限制为最大 32 KB。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p122">The body of the appointment. The body content is limited to a maximum size of 32 KB.</span></span> |

##### <a name="requirements"></a><span data-ttu-id="b5e1f-406">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-406">Requirements</span></span>

|<span data-ttu-id="b5e1f-407">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-407">Requirement</span></span>| <span data-ttu-id="b5e1f-408">值</span><span class="sxs-lookup"><span data-stu-id="b5e1f-408">Value</span></span>|
|---|---|
|[<span data-ttu-id="b5e1f-409">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="b5e1f-409">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="b5e1f-410">1.0</span><span class="sxs-lookup"><span data-stu-id="b5e1f-410">1.0</span></span>|
|[<span data-ttu-id="b5e1f-411">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="b5e1f-411">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="b5e1f-412">ReadItem</span><span class="sxs-lookup"><span data-stu-id="b5e1f-412">ReadItem</span></span>|
|[<span data-ttu-id="b5e1f-413">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="b5e1f-413">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="b5e1f-414">阅读</span><span class="sxs-lookup"><span data-stu-id="b5e1f-414">Read</span></span>|

##### <a name="example"></a><span data-ttu-id="b5e1f-415">示例</span><span class="sxs-lookup"><span data-stu-id="b5e1f-415">Example</span></span>

```js
var start = new Date();
var end = new Date();
end.setHours(start.getHours() + 1);

Office.context.mailbox.displayNewAppointmentForm(
  {
    requiredAttendees: ['bob@contoso.com'],
    optionalAttendees: ['sam@contoso.com'],
    start: start,
    end: end,
    location: 'Home',
    resources: ['projector@contoso.com'],
    subject: 'meeting',
    body: 'Hello World!'
  });
```

#### <a name="getcallbacktokenasyncoptions-callback"></a><span data-ttu-id="b5e1f-416">getCallbackTokenAsync([options], callback)</span><span class="sxs-lookup"><span data-stu-id="b5e1f-416">getCallbackTokenAsync([options], callback)</span></span>

<span data-ttu-id="b5e1f-417">获取一个包含用于调用 REST API 或 Exchange Web 服务的令牌的字符串。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-417">Gets a string that contains a token used to call REST APIs or Exchange Web Services.</span></span>

<span data-ttu-id="b5e1f-p123">`getCallbackTokenAsync` 方法进行异步调用，从托管用户邮箱的 Exchange Server 获取非跳转令牌。回调令牌的生存期为 5 分钟。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p123">The `getCallbackTokenAsync` method makes an asynchronous call to get an opaque token from the Exchange Server that hosts the user's mailbox. The lifetime of the callback token is 5 minutes.</span></span>

> [!NOTE]
> <span data-ttu-id="b5e1f-420">建议外接程序而不是 Exchange Web 服务尽可能使用 REST Api。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-420">It is recommended that add-ins use the REST APIs instead of Exchange Web Services whenever possible.</span></span> 

<span data-ttu-id="b5e1f-421">**REST 令牌**</span><span class="sxs-lookup"><span data-stu-id="b5e1f-421">**REST Tokens**</span></span>

<span data-ttu-id="b5e1f-p124">请求 REST 令牌时 (`options.isRest = true`) 时，生成的令牌将无法对 Exchange Web 服务调用进行身份验证。令牌的作用域限制为对当前项及其附件的只读访问，除非外接程序在其清单中指定了 [`ReadWriteMailbox`](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions#readwritemailbox-permission) 权限。如果指定了 `ReadWriteMailbox` 权限，则生成的令牌将授予对邮件、日历和联系人的读/写权限，包括发送邮件的功能。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p124">When a REST token is requested (`options.isRest = true`), the resulting token will not work to authenticate Exchange Web Services calls. The token will be limited in scope to read-only access to the current item and its attachments, unless the add-in has specified the [`ReadWriteMailbox`](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions#readwritemailbox-permission) permission in its manifest. If the `ReadWriteMailbox` permission is specified, the resulting token will grant read/write access to mail, calendar, and contacts, including the ability to send mail.</span></span>

<span data-ttu-id="b5e1f-425">在进行 REST API 调用时，外接程序应使用 `restUrl` 属性来确定要使用的正确 URL。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-425">The add-in should use the `restUrl` property to determine the correct URL to use when making REST API calls.</span></span>

<span data-ttu-id="b5e1f-426">**EWS 令牌**</span><span class="sxs-lookup"><span data-stu-id="b5e1f-426">**EWS Tokens**</span></span>

<span data-ttu-id="b5e1f-p125">请求 EWS 令牌 (`options.isRest = false`) 时，生成的令牌将无法对 REST API 调用进行身份验证。令牌的作用域限制为访问当前项。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p125">When an EWS token is requested (`options.isRest = false`), the resulting token will not work to authenticate REST API calls. The token will be limited in scope to accessing the current item.</span></span>

<span data-ttu-id="b5e1f-429">外接程序应使用 `ewsUrl` 属性来确定进行 EWS 调用时要使用的正确 URL。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-429">The add-in should use the `ewsUrl` property to determine the correct URL to use when making EWS calls.</span></span>

##### <a name="parameters"></a><span data-ttu-id="b5e1f-430">参数：</span><span class="sxs-lookup"><span data-stu-id="b5e1f-430">Parameters:</span></span>

|<span data-ttu-id="b5e1f-431">名称</span><span class="sxs-lookup"><span data-stu-id="b5e1f-431">Name</span></span>| <span data-ttu-id="b5e1f-432">类型</span><span class="sxs-lookup"><span data-stu-id="b5e1f-432">Type</span></span>| <span data-ttu-id="b5e1f-433">属性</span><span class="sxs-lookup"><span data-stu-id="b5e1f-433">Attributes</span></span>| <span data-ttu-id="b5e1f-434">说明</span><span class="sxs-lookup"><span data-stu-id="b5e1f-434">Description</span></span>|
|---|---|---|---|
| `options` | <span data-ttu-id="b5e1f-435">对象</span><span class="sxs-lookup"><span data-stu-id="b5e1f-435">Object</span></span> | <span data-ttu-id="b5e1f-436">&lt;可选&gt;</span><span class="sxs-lookup"><span data-stu-id="b5e1f-436">&lt;optional&gt;</span></span> | <span data-ttu-id="b5e1f-437">包含一个或多个以下属性的对象文本。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-437">An object literal that contains one or more of the following properties.</span></span> |
| `options.isRest` | <span data-ttu-id="b5e1f-438">布尔值</span><span class="sxs-lookup"><span data-stu-id="b5e1f-438">Boolean</span></span> |  <span data-ttu-id="b5e1f-439">&lt;可选&gt;</span><span class="sxs-lookup"><span data-stu-id="b5e1f-439">&lt;optional&gt;</span></span> | <span data-ttu-id="b5e1f-p126">确定所提供的令牌是否将用于 Outlook REST API 或 Exchange Web 服务。默认值为 `false`。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p126">Determines if the token provided will be used for the Outlook REST APIs or Exchange Web Services. Default value is `false`.</span></span> |
| `options.asyncContext` | <span data-ttu-id="b5e1f-442">对象</span><span class="sxs-lookup"><span data-stu-id="b5e1f-442">Object</span></span> |  <span data-ttu-id="b5e1f-443">&lt;可选&gt;</span><span class="sxs-lookup"><span data-stu-id="b5e1f-443">&lt;optional&gt;</span></span> | <span data-ttu-id="b5e1f-444">传递给异步方法的任何状态数据。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-444">Any state data that is passed to the asynchronous method.</span></span> |
|`callback`| <span data-ttu-id="b5e1f-445">函数</span><span class="sxs-lookup"><span data-stu-id="b5e1f-445">function</span></span>||<span data-ttu-id="b5e1f-p127">方法完成后，使用单个参数 `callback`（一个 [`asyncResult`](/javascript/api/office/office.asyncresult) 对象）调用在 `AsyncResult` 参数中传递的函数。令牌作为 `asyncResult.value` 属性中的字符串提供。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p127">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object. The token is provided as a string in the `asyncResult.value` property.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="b5e1f-448">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-448">Requirements</span></span>

|<span data-ttu-id="b5e1f-449">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-449">Requirement</span></span>| <span data-ttu-id="b5e1f-450">值</span><span class="sxs-lookup"><span data-stu-id="b5e1f-450">Value</span></span>|
|---|---|
|[<span data-ttu-id="b5e1f-451">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="b5e1f-451">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="b5e1f-452">1.5</span><span class="sxs-lookup"><span data-stu-id="b5e1f-452">1.5</span></span> |
|[<span data-ttu-id="b5e1f-453">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="b5e1f-453">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="b5e1f-454">ReadItem</span><span class="sxs-lookup"><span data-stu-id="b5e1f-454">ReadItem</span></span>|
|[<span data-ttu-id="b5e1f-455">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="b5e1f-455">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="b5e1f-456">撰写和阅读</span><span class="sxs-lookup"><span data-stu-id="b5e1f-456">Compose and read</span></span>|

##### <a name="example"></a><span data-ttu-id="b5e1f-457">示例</span><span class="sxs-lookup"><span data-stu-id="b5e1f-457">Example</span></span>

```js
function getCallbackToken() {
  var options = {
    isRest: true,
    asyncContext: { message: 'Hello World!' }
  };

  Office.context.mailbox.getCallbackTokenAsync(options, cb);
}

function cb(asyncResult) {
  var token = asyncResult.value;
}
```

#### <a name="getcallbacktokenasynccallback-usercontext"></a><span data-ttu-id="b5e1f-458">getCallbackTokenAsync(callback, [userContext])</span><span class="sxs-lookup"><span data-stu-id="b5e1f-458">getCallbackTokenAsync(callback, [userContext])</span></span>

<span data-ttu-id="b5e1f-459">获取一个字符串，其中包含用于从 Exchange Server 获取附件或项目的令牌。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-459">Gets a string that contains a token used to get an attachment or item from an Exchange Server.</span></span>

<span data-ttu-id="b5e1f-p128">`getCallbackTokenAsync` 方法进行异步调用，从托管用户邮箱的 Exchange Server 获取非跳转令牌。回调令牌的生存期为 5 分钟。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p128">The `getCallbackTokenAsync` method makes an asynchronous call to get an opaque token from the Exchange Server that hosts the user's mailbox. The lifetime of the callback token is 5 minutes.</span></span>

<span data-ttu-id="b5e1f-p129">可以将令牌和附件标识符或项标识符传递到第三方系统。第三方系统使用令牌作为持有者身份验证令牌调用 Exchange Web 服务 (EWS) [GetAttachment](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getattachment-operation) 或 [GetItem](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getitem-operation)，以返回附件或项目。例如，可以创建远程服务来[获取选定项目中的附件](https://docs.microsoft.com/outlook/add-ins/get-attachments-of-an-outlook-item)。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p129">You can pass the token and an attachment identifier or item identifier to a third-party system. The third-party system uses the token as a bearer authorization token to call the Exchange Web Services (EWS) [GetAttachment](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getattachment-operation) or [GetItem](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getitem-operation) operation to return an attachment or item. For example, you can create a remote service to [get attachments from the selected item](https://docs.microsoft.com/outlook/add-ins/get-attachments-of-an-outlook-item).</span></span>

<span data-ttu-id="b5e1f-465">应用必须在其清单中指定拥有 **ReadItem** 权限，才能调用阅读模式中的 `getCallbackTokenAsync` 方法。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-465">Your app must have the **ReadItem** permission specified in its manifest to call the `getCallbackTokenAsync` method in read mode.</span></span>

<span data-ttu-id="b5e1f-p130">在撰写模式中，必须调用 [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) 方法来获取传递给 `getCallbackTokenAsync` 方法的项目标识符。应用必须具有调用 `saveAsync` 方法的 **ReadWriteItem** 权限。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p130">In compose mode you must call the [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) method to get an item identifier to pass to the `getCallbackTokenAsync` method. Your app must have **ReadWriteItem** permissions to call the `saveAsync` method.</span></span>

##### <a name="parameters"></a><span data-ttu-id="b5e1f-468">参数：</span><span class="sxs-lookup"><span data-stu-id="b5e1f-468">Parameters:</span></span>

|<span data-ttu-id="b5e1f-469">名称</span><span class="sxs-lookup"><span data-stu-id="b5e1f-469">Name</span></span>| <span data-ttu-id="b5e1f-470">类型</span><span class="sxs-lookup"><span data-stu-id="b5e1f-470">Type</span></span>| <span data-ttu-id="b5e1f-471">属性</span><span class="sxs-lookup"><span data-stu-id="b5e1f-471">Attributes</span></span>| <span data-ttu-id="b5e1f-472">说明</span><span class="sxs-lookup"><span data-stu-id="b5e1f-472">Description</span></span>|
|---|---|---|---|
|`callback`| <span data-ttu-id="b5e1f-473">函数</span><span class="sxs-lookup"><span data-stu-id="b5e1f-473">function</span></span>||<span data-ttu-id="b5e1f-p131">方法完成后，使用单个参数 `callback`（一个 [`asyncResult`](/javascript/api/office/office.asyncresult) 对象）调用在 `AsyncResult` 参数中传递的函数。令牌作为 `asyncResult.value` 属性中的字符串提供。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p131">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object. The token is provided as a string in the `asyncResult.value` property.</span></span>|
|`userContext`| <span data-ttu-id="b5e1f-476">对象</span><span class="sxs-lookup"><span data-stu-id="b5e1f-476">Object</span></span>| <span data-ttu-id="b5e1f-477">&lt;可选&gt;</span><span class="sxs-lookup"><span data-stu-id="b5e1f-477">&lt;optional&gt;</span></span>|<span data-ttu-id="b5e1f-478">传递给异步方法的任何状态数据。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-478">Any state data that is passed to the asynchronous method.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="b5e1f-479">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-479">Requirements</span></span>

|<span data-ttu-id="b5e1f-480">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-480">Requirement</span></span>| <span data-ttu-id="b5e1f-481">值</span><span class="sxs-lookup"><span data-stu-id="b5e1f-481">Value</span></span>|
|---|---|
|[<span data-ttu-id="b5e1f-482">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="b5e1f-482">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="b5e1f-483">1.3</span><span class="sxs-lookup"><span data-stu-id="b5e1f-483">1.3</span></span>|
|[<span data-ttu-id="b5e1f-484">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="b5e1f-484">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="b5e1f-485">ReadItem</span><span class="sxs-lookup"><span data-stu-id="b5e1f-485">ReadItem</span></span>|
|[<span data-ttu-id="b5e1f-486">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="b5e1f-486">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="b5e1f-487">撰写和阅读</span><span class="sxs-lookup"><span data-stu-id="b5e1f-487">Compose and read</span></span>|

##### <a name="example"></a><span data-ttu-id="b5e1f-488">示例</span><span class="sxs-lookup"><span data-stu-id="b5e1f-488">Example</span></span>

```js
function getCallbackToken() {
  Office.context.mailbox.getCallbackTokenAsync(cb);
}

function cb(asyncResult) {
  var token = asyncResult.value;
}
```

####  <a name="getuseridentitytokenasynccallback-usercontext"></a><span data-ttu-id="b5e1f-489">getUserIdentityTokenAsync(callback, [userContext])</span><span class="sxs-lookup"><span data-stu-id="b5e1f-489">getUserIdentityTokenAsync(callback, [userContext])</span></span>

<span data-ttu-id="b5e1f-490">获取用于标识用户和 Office 外接程序的令牌。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-490">Gets a token identifying the user and the Office Add-in.</span></span>

<span data-ttu-id="b5e1f-491">`getUserIdentityTokenAsync` 方法返回你可以用于在第三方系统上识别和 [验证外接程序和用户的令牌](https://docs.microsoft.com/outlook/add-ins/authentication)。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-491">The `getUserIdentityTokenAsync` method returns a token that you can use to identify and [authenticate the add-in and user with a third-party system](https://docs.microsoft.com/outlook/add-ins/authentication).</span></span>

##### <a name="parameters"></a><span data-ttu-id="b5e1f-492">参数：</span><span class="sxs-lookup"><span data-stu-id="b5e1f-492">Parameters:</span></span>

|<span data-ttu-id="b5e1f-493">名称</span><span class="sxs-lookup"><span data-stu-id="b5e1f-493">Name</span></span>| <span data-ttu-id="b5e1f-494">类型</span><span class="sxs-lookup"><span data-stu-id="b5e1f-494">Type</span></span>| <span data-ttu-id="b5e1f-495">属性</span><span class="sxs-lookup"><span data-stu-id="b5e1f-495">Attributes</span></span>| <span data-ttu-id="b5e1f-496">说明</span><span class="sxs-lookup"><span data-stu-id="b5e1f-496">Description</span></span>|
|---|---|---|---|
|`callback`| <span data-ttu-id="b5e1f-497">函数</span><span class="sxs-lookup"><span data-stu-id="b5e1f-497">function</span></span>||<span data-ttu-id="b5e1f-498">方法完成后，使用单个参数 `asyncResult`（一个 [`AsyncResult`](/javascript/api/office/office.asyncresult) 对象）调用在 `callback` 参数中传递的函数。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-498">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object.</span></span><br/><br/><span data-ttu-id="b5e1f-499">令牌作为 `asyncResult.value` 属性中的字符串提供。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-499">The token is provided as a string in the `asyncResult.value` property.</span></span>|
|`userContext`| <span data-ttu-id="b5e1f-500">对象</span><span class="sxs-lookup"><span data-stu-id="b5e1f-500">Object</span></span>| <span data-ttu-id="b5e1f-501">&lt;可选&gt;</span><span class="sxs-lookup"><span data-stu-id="b5e1f-501">&lt;optional&gt;</span></span>|<span data-ttu-id="b5e1f-502">传递给异步方法的任何状态数据。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-502">Any state data that is passed to the asynchronous method.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="b5e1f-503">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-503">Requirements</span></span>

|<span data-ttu-id="b5e1f-504">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-504">Requirement</span></span>| <span data-ttu-id="b5e1f-505">值</span><span class="sxs-lookup"><span data-stu-id="b5e1f-505">Value</span></span>|
|---|---|
|[<span data-ttu-id="b5e1f-506">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="b5e1f-506">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="b5e1f-507">1.0</span><span class="sxs-lookup"><span data-stu-id="b5e1f-507">1.0</span></span>|
|[<span data-ttu-id="b5e1f-508">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="b5e1f-508">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="b5e1f-509">ReadItem</span><span class="sxs-lookup"><span data-stu-id="b5e1f-509">ReadItem</span></span>|
|[<span data-ttu-id="b5e1f-510">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="b5e1f-510">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="b5e1f-511">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="b5e1f-511">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="b5e1f-512">示例</span><span class="sxs-lookup"><span data-stu-id="b5e1f-512">Example</span></span>

```js
function getIdentityToken() {
  Office.context.mailbox.getUserIdentityTokenAsync(cb);
}

function cb(asyncResult) {
  var token = asyncResult.value;
}
```

####  <a name="makeewsrequestasyncdata-callback-usercontext"></a><span data-ttu-id="b5e1f-513">makeEwsRequestAsync(data, callback, [userContext])</span><span class="sxs-lookup"><span data-stu-id="b5e1f-513">makeEwsRequestAsync(data, callback, [userContext])</span></span>

<span data-ttu-id="b5e1f-514">向托管用户邮箱的 Exchange 服务器上的 Exchange Web 服务 (EWS) 发出异步请求。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-514">Makes an asynchronous request to an Exchange Web Services (EWS) service on the Exchange server that hosts the user’s mailbox.</span></span>

> [!NOTE]
> <span data-ttu-id="b5e1f-515">在以下方案中不支持此方法。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-515">This method is not supported in the following scenarios.</span></span>
> - <span data-ttu-id="b5e1f-516">在适用于 iOS 的 Outlook 或 Outlook for Android</span><span class="sxs-lookup"><span data-stu-id="b5e1f-516">In Outlook for iOS or Outlook for Android</span></span>
> - <span data-ttu-id="b5e1f-517">外接程序加载时在 Gmail 邮箱</span><span class="sxs-lookup"><span data-stu-id="b5e1f-517">When the add-in is loaded in a Gmail mailbox</span></span>
> 
> <span data-ttu-id="b5e1f-518">在这些情况下外, 接程序应[使用 REST Api](https://docs.microsoft.com/outlook/add-ins/use-rest-api)访问用户的邮箱，而是。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-518">In these cases, add-ins should [use REST APIs](https://docs.microsoft.com/outlook/add-ins/use-rest-api) to access the user's mailbox instead.</span></span>

<span data-ttu-id="b5e1f-519">`makeEwsRequestAsync` 方法代表外接程序将 EWS 请求发送到 Exchange。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-519">The `makeEwsRequestAsync` method sends an EWS request on behalf of the add-in to Exchange.</span></span> <span data-ttu-id="b5e1f-520">有关支持的 EWS 操作的列表，请参阅[调用 web 服务从 Outlook 外接程序](https://docs.microsoft.com/outlook/add-ins/web-services#ews-operations-that-add-ins-support)。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-520">See [Call web services from an Outlook add-in](https://docs.microsoft.com/outlook/add-ins/web-services#ews-operations-that-add-ins-support) for a list of the supported EWS operations.</span></span>

<span data-ttu-id="b5e1f-521">你不能使用 `makeEwsRequestAsync` 方法请求与文件夹关联的项目。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-521">You cannot request Folder Associated Items with the `makeEwsRequestAsync` method.</span></span>

<span data-ttu-id="b5e1f-522">XML 请求必须指定 UTF-8 编码。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-522">The XML request must specify UTF-8 encoding.</span></span>

```xml
<?xml version="1.0" encoding="utf-8"?>
```

<span data-ttu-id="b5e1f-p133">外接程序必须具有 **ReadWriteMailbox** 权限才能使用 `makeEwsRequestAsync` 方法。有关使用 **ReadWriteMailbox** 权限和可使用 `makeEwsRequestAsync` 方法调用 EWS 操作的信息，请参阅[指定访问用户邮箱的邮件外接程序的权限](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p133">Your add-in must have the **ReadWriteMailbox** permission to use the `makeEwsRequestAsync` method. For information about using the **ReadWriteMailbox** permission and the EWS operations that you can call with the `makeEwsRequestAsync` method, see [Specify permissions for mail add-in access to the user's mailbox](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions).</span></span>

> [!NOTE]
> <span data-ttu-id="b5e1f-525">服务器管理员必须设置`OAuthAuthentication`为 true 时，要启用的客户端访问服务器 EWS 目录上`makeEwsRequestAsync`方法来发出 EWS 请求。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-525">The server administrator must set `OAuthAuthentication` to true on the Client Access Server EWS directory to enable the `makeEwsRequestAsync` method to make EWS requests.</span></span>

##### <a name="version-differences"></a><span data-ttu-id="b5e1f-526">版本差异</span><span class="sxs-lookup"><span data-stu-id="b5e1f-526">Version differences</span></span>

<span data-ttu-id="b5e1f-527">当你在较 15.0.4535.1004 版本更早的 Outlook 版本中运行的邮件应用程序中使用 `makeEwsRequestAsync` 方法，应当将编码值设置为 `ISO-8859-1`。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-527">When you use the `makeEwsRequestAsync` method in mail apps running in Outlook versions earlier than version 15.0.4535.1004, you should set the encoding value to `ISO-8859-1`.</span></span>

```xml
<?xml version="1.0" encoding="iso-8859-1"?>
```

<span data-ttu-id="b5e1f-p134">当邮件应用程序运行在 Outlook 网页版中时，您不需要设置编码值。可以通过使用 mailbox.diagnostics.hostName 属性来确定您的邮件应用程序在 Outlook 中还是 Outlook 网页版中运行。可以通过使用 mailbox.diagnostics.hostVersion 属性来确定正在运行的是 Outlook 的哪个版本。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-p134">You do not need to set the encoding value when your mail app is running in Outlook on the web. You can determine whether your mail app is running in Outlook or Outlook on the web by using the mailbox.diagnostics.hostName property. You can determine what version of Outlook is running by using the mailbox.diagnostics.hostVersion property.</span></span>

##### <a name="parameters"></a><span data-ttu-id="b5e1f-531">参数：</span><span class="sxs-lookup"><span data-stu-id="b5e1f-531">Parameters:</span></span>

|<span data-ttu-id="b5e1f-532">名称</span><span class="sxs-lookup"><span data-stu-id="b5e1f-532">Name</span></span>| <span data-ttu-id="b5e1f-533">类型</span><span class="sxs-lookup"><span data-stu-id="b5e1f-533">Type</span></span>| <span data-ttu-id="b5e1f-534">属性</span><span class="sxs-lookup"><span data-stu-id="b5e1f-534">Attributes</span></span>| <span data-ttu-id="b5e1f-535">说明</span><span class="sxs-lookup"><span data-stu-id="b5e1f-535">Description</span></span>|
|---|---|---|---|
|`data`| <span data-ttu-id="b5e1f-536">字符串</span><span class="sxs-lookup"><span data-stu-id="b5e1f-536">String</span></span>||<span data-ttu-id="b5e1f-537">EWS 请求。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-537">The EWS request.</span></span>|
|`callback`| <span data-ttu-id="b5e1f-538">函数</span><span class="sxs-lookup"><span data-stu-id="b5e1f-538">function</span></span>||<span data-ttu-id="b5e1f-539">方法完成后，使用单个参数 `callback`（一个 [`asyncResult`](/javascript/api/office/office.asyncresult) 对象）调用在 `AsyncResult` 参数中传递的函数。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-539">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object.</span></span><br/><br/><span data-ttu-id="b5e1f-540">EWS 调用的 XML 结果作为 `asyncResult.value` 属性中的字符串提供。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-540">The XML result of the EWS call is provided as a string in the `asyncResult.value` property.</span></span> <span data-ttu-id="b5e1f-541">如果结果的大小超过 1 MB，而被返回一条错误消息。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-541">If the result exceeds 1 MB in size, an error message is returned instead.</span></span>|
|`userContext`| <span data-ttu-id="b5e1f-542">对象</span><span class="sxs-lookup"><span data-stu-id="b5e1f-542">Object</span></span>| <span data-ttu-id="b5e1f-543">&lt;可选&gt;</span><span class="sxs-lookup"><span data-stu-id="b5e1f-543">&lt;optional&gt;</span></span>|<span data-ttu-id="b5e1f-544">传递给异步方法的任何状态数据。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-544">Any state data that is passed to the asynchronous method.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="b5e1f-545">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-545">Requirements</span></span>

|<span data-ttu-id="b5e1f-546">要求</span><span class="sxs-lookup"><span data-stu-id="b5e1f-546">Requirement</span></span>| <span data-ttu-id="b5e1f-547">值</span><span class="sxs-lookup"><span data-stu-id="b5e1f-547">Value</span></span>|
|---|---|
|[<span data-ttu-id="b5e1f-548">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="b5e1f-548">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="b5e1f-549">1.0</span><span class="sxs-lookup"><span data-stu-id="b5e1f-549">1.0</span></span>|
|[<span data-ttu-id="b5e1f-550">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="b5e1f-550">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="b5e1f-551">ReadWriteMailbox</span><span class="sxs-lookup"><span data-stu-id="b5e1f-551">ReadWriteMailbox</span></span>|
|[<span data-ttu-id="b5e1f-552">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="b5e1f-552">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="b5e1f-553">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="b5e1f-553">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="b5e1f-554">示例</span><span class="sxs-lookup"><span data-stu-id="b5e1f-554">Example</span></span>

<span data-ttu-id="b5e1f-555">下面的示例调用 `makeEwsRequestAsync` 以使用 `GetItem` 操作来获取项目的主题。</span><span class="sxs-lookup"><span data-stu-id="b5e1f-555">The following example calls `makeEwsRequestAsync` to use the `GetItem` operation to get the subject of an item.</span></span>

```js
function getSubjectRequest(id) {
   // Return a GetItem operation request for the subject of the specified item.
   var request =
    '<?xml version="1.0" encoding="utf-8"?>' +
    '<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"' +
    '               xmlns:xsd="http://www.w3.org/2001/XMLSchema"' +
    '               xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/"' +
    '               xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">' +
    '  <soap:Header>' +
    '    <RequestServerVersion Version="Exchange2013" xmlns="http://schemas.microsoft.com/exchange/services/2006/types" soap:mustUnderstand="0" />' +
    '  </soap:Header>' +
    '  <soap:Body>' +
    '    <GetItem xmlns="http://schemas.microsoft.com/exchange/services/2006/messages">' +
    '      <ItemShape>' +
    '        <t:BaseShape>IdOnly</t:BaseShape>' +
    '        <t:AdditionalProperties>' +
    '            <t:FieldURI FieldURI="item:Subject"/>' +
    '        </t:AdditionalProperties>' +
    '      </ItemShape>' +
    '      <ItemIds><t:ItemId Id="' + id + '"/></ItemIds>' +
    '    </GetItem>' +
    '  </soap:Body>' +
    '</soap:Envelope>';

   return request;
}

function sendRequest() {
   // Create a local variable that contains the mailbox.
   Office.context.mailbox.makeEwsRequestAsync(
    getSubjectRequest(mailbox.item.itemId), callback);
}

function callback(asyncResult)  {
   var result = asyncResult.value;
   var context = asyncResult.asyncContext;

   // Process the returned response here.
}
```