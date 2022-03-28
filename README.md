
#### 초기 세팅

yarn add @react-navigation/native @react-navigation/native-stack @react-navigation/bottom-tabs react-native-screens react-native-safe-area-context react-native-vector-icons

#### rn-tailwind

설치 : yarn add rn-tailwind


import { TailwindUIProvider } from "rn-tailwind";

const Index = () => (
  <TailwindUIProvider>
    <App />
  </TailwindUIProvider>,
)


import { View, Text } from "rn-tailwind";

const App = () => (
  <View className="h-full xl:h-1/2">
    <View className="pt-12 xl:pt-4 items-center">
      <View className="bg-blue-200 px-3 py-1 rounded-full">
        <Text className="text-blue-800 font-semibold">Gang Gang </Text>
      </View>
    </View>
  </View>
);



####