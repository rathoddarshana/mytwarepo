# mytwarepo

npx react-native bundle --dev false --entry-file index.ts --bundle-output ios/main.jsbundle --platform ios --assets-dest ios

<StandardButton
                            title="Confirm"
                            testID="Confirm"
                            onPress={onProceed}
                        />


<ProceedModal
                                visible={modalVisible}
                                onClose={() => setModalVisible(false)}
                                onProceed={
                                    onProceedBtnPress
                                }
                            />

                            
