# GSN-Firma

import SwiftUI

struct ContentView: View {
    var body: some View {
        NavigationView {
            List {
                NavigationLink("العملاء", destination: CustomersView())
                NavigationLink("المنتجات", destination: ProductsView())
                NavigationLink("الفواتير", destination: InvoiceView())
            }
            .navigationTitle("نظام المبيعات")
        }
    }
}
