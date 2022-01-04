# Can-anyone-resolve-this-issue-
**JMeter - my first file is not savable, on every time when I save my file number of errors in log get increasing**




2022-01-04 17:30:01,375 INFO o.a.j.g.a.t.TemplateManager: Reading templates from: D:\apache-jmeter-5.4.3\bin\templates\templates.xml
2022-01-04 17:30:10,494 INFO o.a.j.g.a.Load: Loading file: D:\apache-jmeter-5.4.3\bin\templates\build-web-test-plan.jmx
2022-01-04 17:30:11,091 INFO o.a.j.s.SaveService: Testplan (JMX) version: 2.2. Testlog (JTL) version: 2.2
2022-01-04 17:30:11,201 INFO o.a.j.s.SaveService: Using SaveService properties version 5.0
2022-01-04 17:30:11,201 INFO o.a.j.s.SaveService: Using SaveService properties file encoding UTF-8
2022-01-04 17:30:11,201 INFO o.a.j.s.SaveService: Loading file: D:\apache-jmeter-5.4.3\bin\templates\build-web-test-plan.jmx
2022-01-04 17:30:11,279 INFO o.a.j.p.h.c.CookieManager: Settings: Delete null: true Check: true Allow variable: true Save: false Prefix: COOKIE_
2022-01-04 17:30:11,310 INFO o.a.j.p.h.s.HTTPSamplerBase: Parser for text/html is org.apache.jmeter.protocol.http.parser.LagartoBasedHtmlParser
2022-01-04 17:30:11,310 INFO o.a.j.p.h.s.HTTPSamplerBase: Parser for application/xhtml+xml is org.apache.jmeter.protocol.http.parser.LagartoBasedHtmlParser
2022-01-04 17:30:11,310 INFO o.a.j.p.h.s.HTTPSamplerBase: Parser for application/xml is org.apache.jmeter.protocol.http.parser.LagartoBasedHtmlParser
2022-01-04 17:30:11,310 INFO o.a.j.p.h.s.HTTPSamplerBase: Parser for text/xml is org.apache.jmeter.protocol.http.parser.LagartoBasedHtmlParser
2022-01-04 17:30:11,310 INFO o.a.j.p.h.s.HTTPSamplerBase: Parser for text/vnd.wap.wml is org.apache.jmeter.protocol.http.parser.RegexpHTMLParser
2022-01-04 17:30:11,310 INFO o.a.j.p.h.s.HTTPSamplerBase: Parser for text/css is org.apache.jmeter.protocol.http.parser.CssParser
2022-01-04 17:30:11,888 INFO o.a.j.s.SampleResult: Note: Sample TimeStamps are START times
2022-01-04 17:30:11,888 INFO o.a.j.s.SampleResult: sampleresult.default.encoding is set to ISO-8859-1
2022-01-04 17:30:11,888 INFO o.a.j.s.SampleResult: sampleresult.useNanoTime=true
2022-01-04 17:30:11,888 INFO o.a.j.s.SampleResult: sampleresult.nanoThreadSleep=5000
2022-01-04 17:30:12,139 INFO o.a.j.v.ViewResultsFullVisualizer: Add JavaFX to your Java installation if you want to use renderer: org.apache.jmeter.visualizers.RenderInBrowser
2022-01-04 17:30:12,358 ERROR o.a.j.JMeter: Uncaught exception in thread Thread[AWT-EventQueue-0,6,main]
java.lang.IllegalAccessError: class com.github.weisj.darklaf.ui.filechooser.DarkFilePaneUIBridge$DetailsTableModel (in unnamed module @0x45dd4eda) cannot access class sun.awt.shell.ShellFolder (in module java.desktop) because module java.desktop does not export sun.awt.shell to unnamed module @0x45dd4eda
	at com.github.weisj.darklaf.ui.filechooser.DarkFilePaneUIBridge$DetailsTableModel.updateColumnInfo(DarkFilePaneUIBridge.java:1128) ~[darklaf-core-2.5.4.jar:2.5.4]
	at com.github.weisj.darklaf.ui.filechooser.DarkFilePaneUIBridge$DetailsTableModel.<init>(DarkFilePaneUIBridge.java:1115) ~[darklaf-core-2.5.4.jar:2.5.4]
	at com.github.weisj.darklaf.ui.filechooser.DarkFilePaneUIBridge.getDetailsTableModel(DarkFilePaneUIBridge.java:576) ~[darklaf-core-2.5.4.jar:2.5.4]
	at com.github.weisj.darklaf.ui.filechooser.DarkFilePaneUIBridge$SortableListModel.<init>(DarkFilePaneUIBridge.java:1079) ~[darklaf-core-2.5.4.jar:2.5.4]
	at com.github.weisj.darklaf.ui.filechooser.DarkFilePane.createList(DarkFilePane.java:137) ~[darklaf-core-2.5.4.jar:2.5.4]
	at com.github.weisj.darklaf.ui.filechooser.DarkFileChooserUIBridge.createList(DarkFileChooserUIBridge.java:585) ~[darklaf-core-2.5.4.jar:2.5.4]
	at com.github.weisj.darklaf.ui.filechooser.DarkFileChooserUIBridge$MetalFileChooserUIAccessor.createList(DarkFileChooserUIBridge.java:750) ~[darklaf-core-2.5.4.jar:2.5.4]
	at com.github.weisj.darklaf.ui.filechooser.DarkFilePaneUIBridge.setViewType(DarkFilePaneUIBridge.java:376) ~[darklaf-core-2.5.4.jar:2.5.4]
	at com.github.weisj.darklaf.ui.filechooser.DarkFilePaneUIBridge.propertyChange(DarkFilePaneUIBridge.java:890) ~[darklaf-core-2.5.4.jar:2.5.4]
	at java.beans.PropertyChangeSupport.fire(PropertyChangeSupport.java:343) ~[?:?]
	at java.beans.PropertyChangeSupport.firePropertyChange(PropertyChangeSupport.java:335) ~[?:?]
	at java.beans.PropertyChangeSupport.firePropertyChange(PropertyChangeSupport.java:268) ~[?:?]
	at java.awt.Component.firePropertyChange(Component.java:8722) ~[?:?]
	at javax.swing.JComponent.setUI(JComponent.java:733) ~[?:?]
	at javax.swing.JFileChooser.updateUI(JFileChooser.java:1839) ~[?:?]
	at javax.swing.JFileChooser.setup(JFileChooser.java:396) ~[?:?]
	at javax.swing.JFileChooser.<init>(JFileChooser.java:362) ~[?:?]
	at javax.swing.JFileChooser.<init>(JFileChooser.java:309) ~[?:?]
	at org.apache.jmeter.gui.util.FileDialoger.<clinit>(FileDialoger.java:42) ~[ApacheJMeter_core.jar:5.4.3]
	at org.apache.jmeter.gui.action.Load.loadProjectFile(Load.java:156) ~[ApacheJMeter_core.jar:5.4.3]
	at org.apache.jmeter.gui.action.SelectTemplatesDialog.replaceTemplateParametersAndLoad(SelectTemplatesDialog.java:195) ~[ApacheJMeter_core.jar:5.4.3]
	at org.apache.jmeter.gui.action.SelectTemplatesDialog.checkDirtyAndLoad(SelectTemplatesDialog.java:168) ~[ApacheJMeter_core.jar:5.4.3]
	at org.apache.jmeter.gui.action.SelectTemplatesDialog.actionPerformed(SelectTemplatesDialog.java:306) ~[ApacheJMeter_core.jar:5.4.3]
	at javax.swing.AbstractButton.fireActionPerformed(AbstractButton.java:1972) ~[?:?]
	at javax.swing.AbstractButton$Handler.actionPerformed(AbstractButton.java:2313) ~[?:?]
	at javax.swing.DefaultButtonModel.fireActionPerformed(DefaultButtonModel.java:405) ~[?:?]
	at javax.swing.DefaultButtonModel.setPressed(DefaultButtonModel.java:262) ~[?:?]
	at javax.swing.plaf.basic.BasicButtonListener.mouseReleased(BasicButtonListener.java:279) ~[?:?]
	at com.github.weisj.darklaf.ui.button.DarkButtonListener.mouseReleased(DarkButtonListener.java:72) ~[darklaf-core-2.5.4.jar:2.5.4]
	at java.awt.Component.processMouseEvent(Component.java:6626) ~[?:?]
	at javax.swing.JComponent.processMouseEvent(JComponent.java:3389) ~[?:?]
	at java.awt.Component.processEvent(Component.java:6391) ~[?:?]
	at java.awt.Container.processEvent(Container.java:2266) ~[?:?]
	at java.awt.Component.dispatchEventImpl(Component.java:5001) ~[?:?]
	at java.awt.Container.dispatchEventImpl(Container.java:2324) ~[?:?]
	at java.awt.Component.dispatchEvent(Component.java:4833) ~[?:?]
	at java.awt.LightweightDispatcher.retargetMouseEvent(Container.java:4948) ~[?:?]
	at java.awt.LightweightDispatcher.processMouseEvent(Container.java:4575) ~[?:?]
	at java.awt.LightweightDispatcher.dispatchEvent(Container.java:4516) ~[?:?]
	at java.awt.Container.dispatchEventImpl(Container.java:2310) ~[?:?]
	at java.awt.Window.dispatchEventImpl(Window.java:2780) ~[?:?]
	at java.awt.Component.dispatchEvent(Component.java:4833) ~[?:?]
	at java.awt.EventQueue.dispatchEventImpl(EventQueue.java:773) [?:?]
	at java.awt.EventQueue$4.run(EventQueue.java:722) [?:?]
	at java.awt.EventQueue$4.run(EventQueue.java:716) [?:?]
	at java.security.AccessController.doPrivileged(AccessController.java:399) ~[?:?]
	at java.security.ProtectionDomain$JavaSecurityAccessImpl.doIntersectionPrivilege(ProtectionDomain.java:86) ~[?:?]
	at java.security.ProtectionDomain$JavaSecurityAccessImpl.doIntersectionPrivilege(ProtectionDomain.java:97) ~[?:?]
	at java.awt.EventQueue$5.run(EventQueue.java:746) ~[?:?]
	at java.awt.EventQueue$5.run(EventQueue.java:744) ~[?:?]
	at java.security.AccessController.doPrivileged(AccessController.java:399) ~[?:?]
	at java.security.ProtectionDomain$JavaSecurityAccessImpl.doIntersectionPrivilege(ProtectionDomain.java:86) ~[?:?]
	at java.awt.EventQueue.dispatchEvent(EventQueue.java:743) ~[?:?]
	at java.awt.EventDispatchThread.pumpOneEventForFilters(EventDispatchThread.java:203) ~[?:?]
	at java.awt.EventDispatchThread.pumpEventsForFilter(EventDispatchThread.java:124) ~[?:?]
	at java.awt.EventDispatchThread.pumpEventsForFilter(EventDispatchThread.java:117) ~[?:?]
	at java.awt.WaitDispatchSupport$2.run(WaitDispatchSupport.java:191) ~[?:?]
	at java.awt.WaitDispatchSupport$4.run(WaitDispatchSupport.java:236) ~[?:?]
	at java.awt.WaitDispatchSupport$4.run(WaitDispatchSupport.java:234) ~[?:?]
	at java.security.AccessController.doPrivileged(AccessController.java:318) [?:?]
	at java.awt.WaitDispatchSupport.enter(WaitDispatchSupport.java:234) ~[?:?]
	at java.awt.Dialog.show(Dialog.java:1080) ~[?:?]
	at java.awt.Component.show(Component.java:1728) ~[?:?]
	at java.awt.Component.setVisible(Component.java:1675) ~[?:?]
	at java.awt.Window.setVisible(Window.java:1036) ~[?:?]
	at java.awt.Dialog.setVisible(Dialog.java:1016) ~[?:?]
	at org.apache.jmeter.gui.action.TemplatesCommand.doActionAfterCheck(TemplatesCommand.java:47) ~[ApacheJMeter_core.jar:5.4.3]
	at org.apache.jmeter.gui.action.AbstractActionWithNoRunningTest.doAction(AbstractActionWithNoRunningTest.java:44) ~[ApacheJMeter_core.jar:5.4.3]
	at org.apache.jmeter.gui.action.ActionRouter.performAction(ActionRouter.java:87) ~[ApacheJMeter_core.jar:5.4.3]
	at org.apache.jmeter.gui.action.ActionRouter.lambda$actionPerformed$0(ActionRouter.java:69) ~[ApacheJMeter_core.jar:5.4.3]
	at java.awt.event.InvocationEvent.dispatch(InvocationEvent.java:318) ~[?:?]
	at java.awt.EventQueue.dispatchEventImpl(EventQueue.java:771) ~[?:?]
	at java.awt.EventQueue$4.run(EventQueue.java:722) ~[?:?]
	at java.awt.EventQueue$4.run(EventQueue.java:716) ~[?:?]
	at java.security.AccessController.doPrivileged(AccessController.java:399) [?:?]
	at java.security.ProtectionDomain$JavaSecurityAccessImpl.doIntersectionPrivilege(ProtectionDomain.java:86) [?:?]
	at java.awt.EventQueue.dispatchEvent(EventQueue.java:741) [?:?]
	at java.awt.EventDispatchThread.pumpOneEventForFilters(EventDispatchThread.java:203) [?:?]
	at java.awt.EventDispatchThread.pumpEventsForFilter(EventDispatchThread.java:124) [?:?]
	at java.awt.EventDispatchThread.pumpEventsForHierarchy(EventDispatchThread.java:113) [?:?]
	at java.awt.EventDispatchThread.pumpEvents(EventDispatchThread.java:109) [?:?]
	at java.awt.EventDispatchThread.pumpEvents(EventDispatchThread.java:101) [?:?]
	at java.awt.EventDispatchThread.run(EventDispatchThread.java:90) [?:?]
2022-01-04 17:30:28,567 INFO o.a.j.s.FileServer: Default base='D:\apache-jmeter-5.4.3\bin'
2022-01-04 17:30:28,598 INFO o.a.j.v.ViewResultsFullVisualizer: Add JavaFX to your Java installation if you want to use renderer: org.apache.jmeter.visualizers.RenderInBrowser
2022-01-04 17:43:17,506 ERROR o.a.j.JMeter: Uncaught exception in thread Thread[AWT-EventQueue-0,6,main]
java.lang.NoClassDefFoundError: Could not initialize class org.apache.jmeter.gui.util.FileDialoger
	at org.apache.jmeter.gui.action.Save.computeFileName(Save.java:201) ~[ApacheJMeter_core.jar:5.4.3]
	at org.apache.jmeter.gui.action.Save.doAction(Save.java:163) ~[ApacheJMeter_core.jar:5.4.3]
	at org.apache.jmeter.gui.action.ActionRouter.performAction(ActionRouter.java:87) ~[ApacheJMeter_core.jar:5.4.3]
	at org.apache.jmeter.gui.action.ActionRouter.lambda$actionPerformed$0(ActionRouter.java:69) ~[ApacheJMeter_core.jar:5.4.3]
	at java.awt.event.InvocationEvent.dispatch(InvocationEvent.java:318) ~[?:?]
	at java.awt.EventQueue.dispatchEventImpl(EventQueue.java:771) ~[?:?]
	at java.awt.EventQueue$4.run(EventQueue.java:722) ~[?:?]
	at java.awt.EventQueue$4.run(EventQueue.java:716) ~[?:?]
	at java.security.AccessController.doPrivileged(AccessController.java:399) ~[?:?]
	at java.security.ProtectionDomain$JavaSecurityAccessImpl.doIntersectionPrivilege(ProtectionDomain.java:86) ~[?:?]
	at java.awt.EventQueue.dispatchEvent(EventQueue.java:741) ~[?:?]
	at java.awt.EventDispatchThread.pumpOneEventForFilters(EventDispatchThread.java:203) [?:?]
	at java.awt.EventDispatchThread.pumpEventsForFilter(EventDispatchThread.java:124) [?:?]
	at java.awt.EventDispatchThread.pumpEventsForHierarchy(EventDispatchThread.java:113) [?:?]
	at java.awt.EventDispatchThread.pumpEvents(EventDispatchThread.java:109) [?:?]
	at java.awt.EventDispatchThread.pumpEvents(EventDispatchThread.java:101) [?:?]
	at java.awt.EventDispatchThread.run(EventDispatchThread.java:90) [?:?]
