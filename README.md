# PXP_smoke
import static com.kms.katalon.core.checkpoint.CheckpointFactory.findCheckpoint
import static com.kms.katalon.core.testcase.TestCaseFactory.findTestCase
import static com.kms.katalon.core.testdata.TestDataFactory.findTestData
import static com.kms.katalon.core.testobject.ObjectRepository.findTestObject
import com.kms.katalon.core.checkpoint.Checkpoint as Checkpoint
import com.kms.katalon.core.cucumber.keyword.CucumberBuiltinKeywords as CucumberKW
import com.kms.katalon.core.mobile.keyword.MobileBuiltInKeywords as Mobile
import com.kms.katalon.core.model.FailureHandling as FailureHandling
import com.kms.katalon.core.testcase.TestCase as TestCase
import com.kms.katalon.core.testdata.TestData as TestData
import com.kms.katalon.core.testobject.TestObject as TestObject
import com.kms.katalon.core.webservice.keyword.WSBuiltInKeywords as WS
import com.kms.katalon.core.webui.keyword.WebUiBuiltInKeywords as WebUI
import internal.GlobalVariable as GlobalVariable
import org.openqa.selenium.Keys as Keys

WebUI.openBrowser('')

WebUI.maximizeWindow()

WebUI.navigateToUrl('https://int.contentserv.com/qa-1/?login&uilang=en_US&datalang=en_US')

WebUI.setText(findTestObject('Object Repository/Text/Page_Contentserv/input_Username_userNameField'), 'admin')

WebUI.click(findTestObject('Object Repository/Text/Page_Contentserv/span_Next'))

WebUI.setEncryptedText(findTestObject('Object Repository/Text/Page_Contentserv/input_Password_userPasswordField'), 'r98I3Krbh9GKMuVCU6OqlA==')

WebUI.click(findTestObject('Object Repository/Text/Page_Contentserv/span_Log In'))

WebUI.click(findTestObject('Object Repository/Text/Page_Contentserv/div_PIM_menuItem  menuItem settingsMenuItem'))

WebUI.click(findTestObject('Object Repository/Text/Page_Contentserv/div_Classes'))

WebUI.click(findTestObject('Object Repository/Text/Page_Contentserv/div_Properties'))

not_run: WebUI.click(findTestObject('Object Repository/Text/Page_Contentserv/div_Auto Generated'))

not_run: WebUI.click(findTestObject('Object Repository/Text/Page_Contentserv/div_Properties'))

not_run: WebUI.click(findTestObject('Object Repository/Text/Page_Contentserv/div_Properties'))

WebUI.click(findTestObject('Text/Page_Contentserv/div_Text'))

WebUI.click(findTestObject('Object Repository/Text/Page_Contentserv/div_Text_headerButtonIcon create'))

WebUI.click(findTestObject('Object Repository/Text/Page_Contentserv/div_Name_commonConfigSectionElementBody'))

WebUI.setText(findTestObject('Object Repository/Text/Page_Contentserv/input_Name_customTextField singleText'), 'Text')

WebUI.click(findTestObject('Object Repository/Text/Page_Contentserv/span_Create'))

WebUI.click(findTestObject('Object Repository/Text/Page_Contentserv/div_En_userImageWrapper noImage'))

WebUI.click(findTestObject('Object Repository/Text/Page_Contentserv/div_Log Out'))

WebUI.setText(findTestObject('Object Repository/Text/Page_Contentserv/input_Username_userNameField'), 'admin')

WebUI.click(findTestObject('Object Repository/Text/Page_Contentserv/button_Next'))

WebUI.setEncryptedText(findTestObject('Object Repository/Text/Page_Contentserv/input_Password_userPasswordField'), 'r98I3Krbh9GKMuVCU6OqlA==')

WebUI.click(findTestObject('Object Repository/Text/Page_Contentserv/span_Log In'))

WebUI.click(findTestObject('Object Repository/Text/Page_Contentserv/div_PIM_menuItem  menuItem settingsMenuItem'))

WebUI.click(findTestObject('Object Repository/Text/Page_Contentserv/div_Classes_expandIcon expanded'))

WebUI.click(findTestObject('Object Repository/Text/Page_Contentserv/div_Properties'))

WebUI.click(findTestObject('Object Repository/Text/Page_Contentserv/div_Text'))

WebUI.click(findTestObject('Object Repository/Text/Page_Contentserv/div_Text_headerButtonIcon create katalonDeHighlight'))

WebUI.click(findTestObject('Object Repository/Text/Page_Contentserv/span_Cancel'))
